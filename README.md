# Data-Ware-house-Project-
# 📊 Sales Data Warehouse & SQL Analytics Project

## 📌 Project Overview
This project demonstrates the design and analysis of a **Sales Data Warehouse** using MySQL.  
It follows a **star schema** approach with dimension and fact tables to perform business analytics such as revenue analysis, customer behavior, and product performance.

The goal is to showcase **SQL skills for Data Analyst roles**, including table design, data cleaning, transformations, and analytical queries.

---

## 🏗️ Data Warehouse Architecture
The project is organized using a **star schema**:

### ⭐ Dimension Tables
- `dim_customers` – Customer information (name, gender, country, birthdate, etc.)
- `dim_products` – Product details (category, subcategory, price, etc.)

### ⭐ Fact Table
- `fact_sales` – Transactional sales data including:
  - order_number  
  - product_key  
  - customer_key  
  - order_date  
  - quantity  
  - sales_amount  

These tables allow fast analytical queries and reporting.

---

## 🧹 Data Cleaning & Transformation
During loading, the following steps were applied:

- Converted string dates into `DATE` format.
- Handled missing values using `COALESCE`, `NULLIF`, and `TRIM`.
- Standardized empty categories as `N/A`.
- Used surrogate keys for better joins.
- Optimized data types (`DECIMAL` for money, `VARCHAR` for text).

---

## 📈 Business Questions Answered

This project answers real business questions such as:

- Top 5 products generating highest revenue  
- Worst performing products  
- Top 10 customers by revenue  
- Customers with fewest orders  
- Oldest and youngest customers  
- Sales timeline range  
- Revenue contribution by product  

These queries are useful for dashboards and decision-making.

---

## 🛠️ Tools & Technologies

- MySQL  
- MySQL Workbench  
- SQL (DDL, DML, Window Functions)  
- Star Schema Modeling  

-------------------------------------------
