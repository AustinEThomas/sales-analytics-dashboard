# 📊 Sales Analytics Dashboard

An interactive Power BI dashboard I built to analyze sales performance, shipments, profitability, and key business metrics.

> **Note:** All data included in this project is fictional and was created for portfolio purposes. No proprietary or company data is included.

![Power BI](https://img.shields.io/badge/Power%20BI-BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Time%20Intelligence-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![License](https://img.shields.io/badge/License-MIT-blue)

![Dashboard Overview](images/sales-analytics-dashboard.png)

---

# Why I Built This

One of the biggest challenges businesses face is turning large amounts of sales data into information that people can actually use.

I built this dashboard to bring together bookings, shipments, shipment goals, and gross margin into one interactive report. The goal was to make it easy for leadership to monitor performance, identify trends, and compare results over time without digging through spreadsheets.

---

# Dashboard Features

This dashboard includes:

- Executive KPI scorecards
- Monthly shipment trends
- Shipments vs. goal tracking
- Gross margin and profitability analysis
- Year-over-year comparisons
- Interactive filtering by year and date

---

# Behind the Scenes

This portfolio version uses sample Excel files as its data source.

The production version was designed to connect directly to an Amazon RDS (AWS MySQL) database through Power Query, where it refreshed from live business data.

The report uses custom DAX measures for year-over-year comparisons, profitability analysis, KPI calculations, and dynamic reporting.

---

# Repository Structure

```
sales-analytics-dashboard/

dashboard/
    Sales_Analytics_Dashboard.pbix

data/
    Sales_Booked.xlsx
    Sales_Invoiced.xlsx
    Shipments_Goal.xlsx

images/
    sales-analytics-dashboard.png

README.md
```

---

# Getting Started

1. Download or clone the repository.
2. Open the `.pbix` file in Power BI Desktop.
4. If needed, change the DataFolder parameter to be the path to the folder containing the excel files.
5. Refresh the report.

---

# Skills Demonstrated

- Power BI
- DAX
- Power Query
- Data Modeling
- KPI Development
- Time Intelligence
- Data Visualization
- Business Intelligence

---

## About Me

I'm a Data Engineer who enjoys building dashboards, automation, and reporting solutions that turn complex data into something people can actually use.

Feel free to connect!

- **Portfolio:** https://austinethomas.github.io
- **LinkedIn:** https://www.linkedin.com/in/auethomas
- **GitHub:** https://github.com/AustinEThomas
