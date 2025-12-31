# Supermarket-Sales-BA-Project
Business Analyst project using Excel – sales analysis &amp; insights
# Supermarket Sales Performance Analysis (Excel)

## Dataset
Source file: `Supermarket-Sales-Sample-Data.xlsx`  
Records: 70 orders (Jan–Feb 2024)

### Fields
- Order No, Order Date, Ship Date, Customer Name
- Retail Price (USD), Order Quantity, Tax (USD), Total (USD)

## What’s inside the workbook
`Supermarket_Sales_BA_Project.xlsx`

### 1) Raw_Data (cleaned)
- Removed title/blank rows and fixed headers
- Correct data types (dates, currency, numeric)
- Added calculated fields:
  - Subtotal (USD) = Retail Price * Order Quantity
  - Calculated Total (USD) = Subtotal + Tax
  - Total Variance (USD) = Reported Total − Calculated Total
  - Ship Lead Time (days) = Ship Date − Order Date

### 2) Summary_KPIs
Key metrics:
- Total Orders
- Total Revenue (USD)
- Average Order Value (USD)
- Average Units per Order
- Average Ship Lead Time (days)
- Top Customer (Revenue)

### 3) Revenue_by_Customer
Customer-level aggregation:
- Orders, Units, Revenue, Avg Order Value
Includes a **Top 10 Customers by Revenue** chart.

### 4) Sales_Trend
Daily trend:
- Orders, Units, Revenue
Includes a **Revenue Trend by Order Date** line chart.

### 5) Quantity_vs_Revenue
Quantity band analysis:
- Orders, Revenue, Avg Order Value
Includes a **Revenue by Order Quantity** chart.

### 6) Insights_Recommendations
Business insights and actionable recommendations for stakeholders.

## Skills demonstrated
- Data cleaning & validation
- KPI definition
- Aggregation & segmentation
- Executive-ready reporting
- Visualization and storytelling
