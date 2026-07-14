# SQL Exploratory Data Analysis (EDA)

## Overview
This project performs **Exploratory Data Analysis (EDA)** using SQL to understand business performance, customer behavior, product performance, and sales trends from a relational data warehouse.

## Dataset
The analysis uses a star schema consisting of:
- `gold.fact_sales`
- `gold.dim_customers`
- `gold.dim_products`

## Analysis Performed

### Database Exploration
- Explore database tables and columns
- Inspect schema metadata

### Dimension Analysis
- Customer countries
- Product categories, subcategories, and products

### Date Analysis
- First and last order dates
- Sales history duration
- Youngest and oldest customers

### Business Metrics
- Total Sales
- Total Quantity Sold
- Average Selling Price
- Total Orders
- Total Customers
- Total Products

### Magnitude Analysis
- Customers by country and gender
- Products by category
- Average product cost by category
- Revenue by category
- Revenue by customer
- Sales and quantity by country
- Quantity by category
- Average selling price by product
- Orders by customer

### Ranking Analysis
- Top 5 revenue-generating products
- Bottom 5 products by sales
- Product ranking using SQL Window Functions

## SQL Concepts Used
- SELECT
- DISTINCT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions (`SUM`, `AVG`, `COUNT`, `MIN`, `MAX`)
- JOINs
- UNION ALL
- Window Functions (`ROW_NUMBER()`)
- TOP
- INFORMATION_SCHEMA
- DATEDIFF

## Key Learning Outcomes
- Explore relational databases efficiently
- Generate business KPIs using SQL
- Perform customer, product, and sales analysis
- Build ranking reports with Window Functions
- Extract actionable business insights from transactional data

## Technologies
- SQL Server (T-SQL)
- Relational Data Warehouse
- Star Schema

---
**Author:** Mumtaz Sajid Khan
