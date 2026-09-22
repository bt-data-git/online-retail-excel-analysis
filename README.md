# Online Retail Excel Analysis

## Project Overview
This project analyses a real-world e-commerce transaction dataset to explore revenue trends, product performance, customer purchasing behaviour and order patterns.

The original dataset contained over 500,000 rows. After cleaning the data, I worked with a cleaned sample of approximately 13,000 rows in Excel to keep the analysis manageable while still using realistic transaction data.

I created an Excel dashboard using PivotTables, charts and calculated fields to summarise the main findings.

## Tools Used
- Microsoft Excel
- PivotTables
- Calculated Columns
- Charts
- Data Cleaning
- Data Validation

## Data Cleaning
The dataset was cleaned and prepared before analysis. This included:

- Removing cancelled invoices where invoice numbers started with `C`
- Removing rows with negative quantities
- Removing blank customer IDs
- Removing rows with zero or invalid unit prices
- Creating a calculated `Total Revenue` field using quantity × unit price
- Creating month fields for time-based analysis
- Using distinct invoice numbers when calculating order volume to avoid overcounting product line items

## Analysis
The analysis focused on:

- Revenue by month
- Revenue by country
- Top products by revenue
- Top customers by revenue
- Order volume by month
- Average line-item revenue by month

## Key Findings
- The United Kingdom generated approximately 90% of total revenue, making it the dominant market in the dataset.
- July recorded the highest monthly revenue, followed by February and January.
- The top 10 customers contributed around 25% of total revenue, indicating moderate customer concentration.
- Revenue was concentrated across a relatively small group of high-performing products.
- Order volume required distinct invoice counts because each invoice could contain multiple product line items.

## Dashboard
The final dashboard brings together revenue trends, product performance, customer concentration, country-level sales and order volume.

![E-Commerce Dashboard](E-commerce%20dashboard.png)

## Files
- `E-commerce data analysis.xlsx` — original Excel analysis containing the PivotTables and dashboard
- `E-commerce dashboard.png` — dashboard preview

## Portfolio
This project is also featured in my data analytics portfolio.
