# Supply Chain Finance Management using SQL

## Project Overview

This project focuses on designing and implementing a Supply Chain Finance Management database for AtliQ Hardware, a company specializing in electronic products such as mice, keyboards, laptops, and printers.

The objective is to analyze sales performance, customer behavior, product profitability, freight costs, inventory planning, and demand forecasting using SQL.

---

## Business Problem

AtliQ Hardware operates across multiple markets and sales channels. The company requires a centralized data management system to:

* Track sales transactions
* Monitor customer performance
* Evaluate product profitability
* Analyze freight and manufacturing costs
* Improve demand forecasting
* Optimize inventory management
* Support strategic business decisions

---

## Database Architecture

The project follows a Star Schema Data Warehouse Design consisting of:

### Dimension Tables

#### dim_customer

Stores customer-related information.

Columns:

* customer_code
* customer
* platform
* channel
* market
* sub_zone
* region

#### dim_product

Stores product-related information.

Columns:

* product_code
* division
* segment
* category
* product
* variant

---

### Fact Tables

#### fact_sales_monthly

Stores monthly sales transactions.

#### fact_forecast_monthly

Stores demand forecasting data.

#### fact_gross_price

Stores product prices by fiscal year.

#### fact_manufacturing_cost

Stores manufacturing cost information.

#### fact_freight_cost

Stores freight and logistics costs.

#### fact_pre_invoice_deductions

Stores yearly discount agreements.

#### fact_post_invoice_deductions

Stores promotional discounts, rebates, and placement fees.

---

## ER Diagram

The project follows a star-schema model where dimension tables are connected with multiple fact tables through primary and foreign key relationships.

---

## SQL Concepts Used

### Joins

* Inner Join
* Multiple Table Joins

### Aggregate Functions

* SUM()
* AVG()
* COUNT()

### Conditional Logic

* CASE Statements

### Common Table Expressions (CTE)

### Window Functions

* RANK()
* LAG()

### User Defined Functions (UDF)

### Stored Procedures

### Triggers

### Fiscal Year Calculation

---

## Business Analysis Queries

### 1. Fiscal Year Calculation

Determine fiscal year based on sales date.

### 2. Customer Sales Analysis

Analyze customer purchases and revenue.

### 3. Monthly Sales Trend Analysis

Track sales growth over time.

### 4. Customer Segmentation

Identify high-value customers.

### 5. Product Performance Analysis

Compare products based on quantity sold and revenue.

### 6. Market Expansion Analysis

Evaluate forecast demand across markets.

### 7. Profitability Analysis

Calculate Revenue, Cost, and Profit.

### 8. Discount Impact Analysis

Measure impact of discounts on revenue.

### 9. Freight Cost Analysis

Analyze logistics expenses.

### 10. Seasonal Sales Analysis

Identify seasonal purchasing patterns.

### 11. Forecast Accuracy Analysis

Compare actual sales against forecasts.

### 12. Channel Performance Analysis

Evaluate sales channels performance.

### 13. Geographical Sales Distribution

Analyze revenue by region.

### 14. Customer Lifetime Value (CLV)

Identify most valuable customers.

### 15. Inventory Management Analysis

Compare forecast demand with actual sales.

---

## Key Insights

* Identified top-performing products.
* Evaluated customer contribution to revenue.
* Analyzed gross profit and margins.
* Measured forecast accuracy.
* Assessed freight and operational costs.
* Evaluated customer lifetime value.
* Supported inventory planning decisions.

---

## Technologies Used

* SQL Server / MySQL
* Database Design
* ER Modeling
* Data Warehousing
* Business Analytics

---

## Project Structure

Supply-Chain-Finance-Management

├── README.md

├── SQL_Scripts

│ └── SupplyChainFinanceManagement.sql

├── Documentation

│ ├── Project_Report.docx

│ ├── ER_Diagram.png

│ └── CoachX_Project_Statement.pdf

├── Screenshots

│ ├── Query_Output_1.png

│ ├── Query_Output_2.png

│ └── Query_Output_3.png

└── Business_Insights

└── Insights_Report.pdf

---

## Business Value

This project demonstrates how SQL can be used to transform raw supply chain and financial data into actionable business insights. The analysis supports decision-making in sales, forecasting, inventory management, profitability tracking, and customer performance evaluation.

---

## Author

Sushma M

Business Analyst | SQL | Power BI | Excel | Python

Bengaluru, Karnataka
