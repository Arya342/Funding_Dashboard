# Funding Invoice Dashboard

A comprehensive Python dashboard built with Streamlit and Plotly to visualize and analyze funding invoice data.

## Features

### 📊 Key Metrics
- Total invoices and amounts
- Payment collection rates
- Outstanding balances
- Credit note summaries

### 📈 Visualizations
- Payment status distribution (pie chart)
- Monthly invoice trends (line + bar charts)
- Top students by invoice amount
- Invoice amount distribution histogram
- Course hours vs invoice amount correlation
- Credit note analysis

### 🔍 Interactive Filters
- Date range selection
- Payment status filtering
- Real-time data updates

### 📋 Data Tables
- Recent invoices view
- Recent credit notes view
- Sortable and searchable tables

## Installation

1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Ensure CSV files are in the same directory:
   - `funding_invoices.csv`
   - `funding_invoice_credit_notes.csv`

## Usage

Run the dashboard:
```bash
streamlit run dashboard.py
```

The dashboard will open in your default web browser at `http://localhost:8501`

## Dashboard Sections

1. **Key Metrics**: High-level financial KPIs
2. **Overview Charts**: Payment status and monthly trends
3. **Financial Analysis**: Student rankings and amount distributions
4. **Credit Note Analysis**: Credit note status and trends
5. **Data Tables**: Recent transactions and details

## Calculations Included

- Total invoice amounts and payments
- Collection rates and outstanding balances
- Monthly aggregations and trends
- Student-wise summaries
- Credit note reconciliation
- Payment status breakdowns

## Technical Details

- **Frontend**: Streamlit with custom CSS styling
- **Visualizations**: Plotly Express and Graph Objects
- **Data Processing**: Pandas with automatic type conversion
- **Caching**: Streamlit caching for performance optimization
- **Responsive Design**: Mobile-friendly layout
