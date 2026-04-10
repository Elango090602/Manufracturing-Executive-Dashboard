# 🚀 Manufacturing Executive Dashboard | Power BI Project

<p align="center">
  <img src="Images\Executive.png" alt="Executive Dashboard Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Language-DAX-1F4E79?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Prep-Power%20Query-217346?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Manufacturing-5B5EA6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-2E8B57?style=for-the-badge" />
</p>

---

## 📌 Project Summary

This project is a **multi-page Power BI dashboard solution** built for a manufacturing business to monitor performance across:

- Executive overview
- Customer sales
- Finance
- Inventory

The goal of this project is to help decision-makers track KPIs, monitor business health, identify operational gaps, and support strategic decisions using interactive dashboards.

---

## 🎯 Business Problem

Manufacturing companies generate data across multiple departments, but that data often stays scattered across separate systems.

This creates problems such as:

- no single view of business performance
- difficulty tracking revenue, cost, and profitability
- weak visibility into customer and product performance
- stock inefficiencies and dead inventory
- no quick way to monitor production efficiency

This dashboard solves that by bringing all major business functions into a **single executive reporting system**.

---

## 🧩 Dashboard Modules

## 1) Executive Dashboard

Provides a high-level snapshot of business performance with KPIs and operational summaries.

### Key Metrics:
- Units Sold
- Revenue
- Expenses
- Gross Profit
- Net Profit
- Budget vs Actual Spend
- OEE Factors
- Shift-wise Production
- Top Selling Products
- Top Customers
- Cost by Department
- Stock Trend Over Time

<p align="center">
  <img src="Images/executive-dashboard.png" alt="Executive Dashboard" width="100%">
</p>

---

## 2) Customer Sales Dashboard

Focused on customer performance, revenue generation, conversion, and retention.

### Key Metrics:
- Total Revenue
- Completed Orders
- Won Conversion
- Top Selling Product
- Avg Retention Rate
- Revenue by Region
- Actual Sales vs Revenue
- Conversion Status
- Top 5 Customers
- Order Status
- Retention Breakdown

<p align="center">
  <img src="Images/customer-sales-dashboard.png" alt="Customer Sales Dashboard" width="100%">
</p>

---

## 3) Finance Dashboard

Designed to track revenue, profitability, and financial trends across products, countries, and departments.

### Key Metrics:
- Sales
- COGM
- Profit
- Units Sold
- Monthly Sales Trend
- Product-wise Sales Trend
- Sales by Country
- Sales by Department

<p align="center">
  <img src="Images/finance-dashboard.png" alt="Finance Dashboard" width="100%">
</p>

---

## 4) Inventory Dashboard

Helps monitor stock levels, material performance, lead times, and inventory movement.

### Key Metrics:
- Inventory Value
- Raw Material Stock
- Finished Goods Stock
- Dead Stock
- Total Consumption
- Avg Turnover Ratio
- Avg Lead Days
- Material Details
- Delivery Status
- Top Materials by Quantity
- Stock Trend Over Time

<p align="center">
  <img src="Images/inventory-dashboard.png" alt="Inventory Dashboard" width="100%">
</p>

---

## 📊 KPI Highlights

### Executive KPIs
- Revenue
- Gross Profit
- Net Profit
- Expenses
- Units Sold

### Production KPIs
- Shift-wise Production
- Availability
- Performance
- Quality
- OEE

### Customer KPIs
- Completed Orders
- Conversion Rate
- Retention Rate
- Top Customers
- Regional Revenue

### Inventory KPIs
- Inventory Value
- RM Stock
- FG Stock
- Dead Stock
- Lead Days
- Turnover Ratio

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development and reporting |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI calculations and measures |
| **Excel / CSV** | Data source and structured inputs |
| **Data Modeling** | Relationship building and reporting structure |

---

## 📁 Project Structure

```bash
manufacturing-executive-dashboard/
│
├── README.md
├── .gitignore
│
├── Dashboard/
│   └── Manufacturing_Dashboard.pbix
│
├── Images/
│   ├── executive-dashboard.png
│   ├── customer-sales-dashboard.png
│   ├── finance-dashboard.png
│   └── inventory-dashboard.png
│
├── Data/
│   ├── sample_data.xlsx
│   └── data_dictionary.xlsx
│
└── Docs/
    ├── business-problem.md
    ├── kpi-list.md
    └── insights-summary.md