# Sales Dashboard - Tableau

## Overview

This project presents an interactive Sales Dashboard developed in Tableau to help business stakeholders and analysts monitor sales performance, profitability, and order quantities through a single centralized view.

The dashboard provides year-over-year KPI comparisons, geographic sales analysis, customer segmentation insights, and dynamic measure selection for enhanced decision-making.

## Dashboard Features

### KPI Monitoring
- Total Sales
- Total Profit
- Total Quantity Sold
- Year-over-Year Performance Comparison
- Trend Sparklines

### Geographic Analysis
- Sales and Profit by State
- US State Hexmap Visualization
- Regional Sales Performance

### Customer & Product Insights
- Monthly Sales by Customer Segment
- Sales Performance by Region
- State-Level Average Sales and Profit Analysis

### Interactive Functionality
- Cross-sheet filtering
- Dynamic parameter-driven metric selection
- Interactive drill-down capabilities
- Linked dashboard actions

## Dashboard Components

| Component | Description |
|------------|-------------|
| Sales KPI | Current vs Previous Year Sales |
| Profit KPI | Current vs Previous Year Profit |
| Quantity KPI | Current vs Previous Year Quantity |
| Sales Sparkline | Monthly Sales Trend |
| Profit Sparkline | Monthly Profit Trend |
| Quantity Sparkline | Monthly Quantity Trend |
| Sales & Profit by State | Geographic Analysis |
| AVG Sales by State | State Performance Benchmark |
| AVG Profit by State | Profit Benchmark Analysis |
| Monthly Sales by Segment | Customer Segment Analysis |
| Total Sales by Location & Manager | Hexmap Visualization |
| Region Wise Sales | Regional Performance Analysis |

## Data Source

The dashboard uses transactional sales data containing:

- Orders
- Customers
- Products
- Geography
- Sales Metrics

### Key Fields
- Order ID
- Order Date
- Customer Name
- Segment
- State
- Region
- Category
- Sales
- Quantity
- Profit
- Discount

## Calculated Metrics

### Sales Metrics
- Total Current Year Sales
- Total Last Year Sales
- Year-on-Year Sales Growth

### Profit Metrics
- Total Current Year Profit
- Total Last Year Profit
- Year-on-Year Profit Growth

### Quantity Metrics
- Total Current Year Quantity
- Total Last Year Quantity
- Year-on-Year Quantity Growth

### Dynamic Measures
Users can switch between:
- Sales
- Profit
- Quantity

using a parameter-driven control.

## Technologies Used

- Tableau Desktop 2026.1
- Microsoft Excel
- Data Visualization
- Business Intelligence (BI)

## Dashboard Interactivity

The dashboard includes:
- 11 Cross-Filter Actions
- Dynamic Measure Parameter
- Interactive State Selection
- Drill-Down Analysis
- Linked Visualizations

## Color Palette

| Color | Hex Code | Purpose |
|---------|---------|---------|
| Blue | #4E79A7 | Positive / Above Average |
| Red | #E15759 | Negative / Below Average |

## Business Value

This dashboard helps organizations:

- Monitor key sales KPIs
- Identify profitable regions
- Compare state-level performance
- Analyze customer segments
- Track year-over-year growth
- Support data-driven decision making

## Project Structure

```
Sales-Dashboard/
│
├── Dashboard/
│   └── Sales_Dashboard.twbx
│
├── Data/
│   ├── Sales_Data.xlsx
│   └── hexmap.xlsx
│
├── Documentation/
│   └── Sales_Dashboard_Report.pdf
│
└── README.md
```

## Future Improvements

- Forecasting and trend prediction
- Customer lifetime value analysis
- Product profitability dashboard
- Real-time data integration
- Executive summary dashboard

## Author

Arif  
Master's Student in Data Analytics

---
Built using Tableau for business intelligence and sales performance analysis.
