# 📊 Sales Analytics Dashboard

> An interactive Power BI dashboard for monitoring sales performance, profitability, and operational KPIs using Power BI, DAX, Power Query, and dimensional data modeling.

![Dashboard Overview](images/dashboard-overview.png)

---

# Overview

The Sales Analytics Dashboard is a business intelligence solution built in **Microsoft Power BI** that provides executives and business leaders with a centralized view of sales performance.

The dashboard combines bookings, shipments, profitability, and operational metrics into a single interactive report that supports strategic decision-making through dynamic filtering, KPI monitoring, and year-over-year analysis.

This project demonstrates advanced Power BI development techniques including custom DAX calculations, Power Query transformations, dimensional modeling, time intelligence, KPI reporting, and interactive visual design.

**Note:** All data included in this repository is **fictional** and was generated solely for portfolio and demonstration purposes. No proprietary or confidential company information is included.

---

# Dashboard Features

## Executive KPI Scorecards

Monitor high-level business performance through dynamic KPI cards including:

- Total Bookings
- Total Shipments
- Shipment Goal
- Gross Margin
- Gross Margin %
- Booked Lines
- Shipped Lines

Each KPI includes:

- Current value
- Year-over-Year comparison
- Color-coded performance indicators
- Dynamic filtering

---

## Sales vs Goal Analysis

Compare monthly shipment performance against predefined operational goals.

Features include:

- Monthly shipment totals
- Goal tracking
- Variance visualization
- Performance monitoring

---

## Year-over-Year Sales Trends

Analyze shipment performance over multiple years.

Capabilities include:

- Current Year vs Previous Year
- Trend analysis
- Seasonal comparison
- Dynamic filtering

---

## Gross Margin Analysis

Monitor company profitability using:

- Gross Margin dollars
- Gross Margin %
- COGS comparison
- Monthly profitability trends

---

## Interactive Filtering

The report includes interactive slicers allowing users to filter by:

- Year
- Date

All visuals update automatically based on user selections.

---

# Technical Features

## Data Modeling

The report utilizes a relational data model built from multiple fact tables.

Primary datasets include:

- Sales Bookings
- Sales Invoices
- Shipment Goals
- Date Dimension

---

## Power Query

Data preparation includes:

- Data cleansing
- Data type conversion
- Column transformations
- Query optimization
- Data loading

---

## DAX

Advanced DAX measures were developed for:

- Year-over-Year calculations
- Gross Margin
- Gross Margin %
- Shipment Goals
- KPI calculations
- Dynamic comparisons
- Time Intelligence
- Conditional formatting
- Variance analysis

---

## Time Intelligence

Implemented using custom DAX measures including:

- Previous Year comparisons
- Dynamic date filtering
- Current period calculations
- Rolling comparisons

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard Development |
| DAX | Business Logic & Measures |
| Power Query | ETL & Data Transformation |
| Excel | Sample Data Source |
| Data Modeling | Relational Analytics |

---

# Repository Structure

```
sales-analytics-dashboard
│
├── dashboard
│   └── SalesPerformance.pbix
│
├── data
│   ├── Sales_Booked.xlsx
│   ├── Sales_Invoiced.xlsx
│   └── Shipments_Goal.xlsx
│
├── images
│   └── dashboard-overview.png
│
└── README.md
```

---

# Dashboard Preview

![Dashboard](images/dashboard-overview.png)

---

# Skills Demonstrated

This project demonstrates experience with:

- Business Intelligence
- Dashboard Design
- Executive Reporting
- Data Modeling
- Power Query
- DAX Development
- Time Intelligence
- KPI Design
- Data Visualization
- Performance Analysis
- Financial Reporting
- Interactive Reporting

---

# Example Business Questions Answered

This dashboard helps answer questions such as:

- Are shipments meeting monthly goals?
- How are bookings trending year-over-year?
- Is profitability improving?
- Which months are underperforming?
- How does gross margin compare across the year?
- Are shipment volumes increasing or decreasing?

---

# Data Disclaimer

All datasets included in this repository are entirely fictional and were created solely for demonstration and portfolio purposes.

This project is intended to showcase Power BI development skills and does not contain any proprietary, confidential, or customer data.

---

# Future Improvements

Potential future enhancements include:

- Customer-level drill-through pages
- Product performance analysis
- Geographic sales mapping
- Forecasting models
- Inventory analytics
- Sales representative scorecards
- Role-Level Security (RLS)
- Incremental Refresh
- SQL database integration
- REST API integration

---

# Author

**Austin Thomas**

Data Engineer | Business Intelligence Developer

GitHub: https://github.com/AustinEThomas

LinkedIn: https://www.linkedin.com/in/auethomas
