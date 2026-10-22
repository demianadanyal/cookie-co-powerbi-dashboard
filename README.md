# Cookie Co. – Wholesale Sales Dashboard (Power BI)

## Overview
Interactive Power BI dashboard analyzing wholesale cookie sales across customers, products, and time.

## Data Preparation (Power Query)
- Fixed data types
- Handled errors and removed duplicates

## Data Modeling
- Built relationships between the 3 tables (Orders, Cookies, Customers)

## DAX
- Calculated columns: Total Sales, Total Revenue (Orders), Selling Price = Cost + Revenue (Cookies)
- Table: Chocolate Chip sales only
- Measures: Total Revenue, Total Profit, Units Sold, Orders

## Dashboard Features
- KPI cards: Total Revenue, Total Profit, Units Sold, Orders
- Slicers: Cookie Type, Customers
- Charts: Revenue by Customer, Revenue Share by Product, Revenue by Year, Revenue by Cookie Type

## Tools
Power BI, Power Query, DAX

## Dashboard Preview


![Dashboard](cookies.png)



## Key Insights
- Total revenue reached 7M with a profit of 4.67M across 699 orders.
- Chocolate Chip is the top-selling cookie (2.4M), followed by White Chocolate Macadamia Nut (1.4M). Fortune Cookie is the lowest (0.2M).
- ACME Bites is the highest-revenue customer.
- Revenue shows a steady upward trend from Jan 2019 to Jan 2020.
