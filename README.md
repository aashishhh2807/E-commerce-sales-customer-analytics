# E-Commerce Sales & Customer Analytics System

## Overview
This project implements a **relational e-commerce database and analytics system** using **MySQL** to analyze customer behavior, sales performance, products, categories, sellers, payments, and reviews.

- Designed and implemented a **relational database** with customers, orders, products, categories, sellers, payments, reviews, and order items
- Developed **advanced SQL queries** using JOINs, subqueries, views, aggregate functions, CASE statements, and window functions
- Performed **customer, product, category, seller, and sales analysis** to extract meaningful business insights
- Implemented analytical queries for **rankings, monthly sales trends, revenue analysis, product ratings, and customer purchasing behavior**

The project focuses on converting transactional e-commerce data into useful business insights through SQL-based analysis.

---

## Features

- Relational e-commerce database design
- Customer spending and purchasing analysis
- Product and category performance analysis
- Seller revenue and performance analysis
- Monthly sales and order trend analysis
- Product rating and review analysis
- Customer and product ranking
- Cross-category customer analysis
- Top-selling product identification

---

## Database Tables

- Customers
- Orders
- Order Items
- Products
- Categories
- Sellers
- Payments
- Reviews

---

## SQL Concepts Used

- `SELECT`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- `DISTINCT`
- `INNER JOIN`
- `LEFT JOIN`
- Multi-table JOINs
- Subqueries
- Derived tables
- Aggregate functions
- `CASE` statements
- Views
- CTEs
- `RANK()`
- `DENSE_RANK()`
- `ROW_NUMBER()`
- `LAG()`
- `LEAD()`
- `DATE_FORMAT()`

---

## File Structure

```text
ecommerce-sales-customer-analytics
├── database
│   ├── schema.sql
│   └── sample_data.sql
│
├── queries
│   ├── customer_analytics.sql
│   ├── product_analytics.sql
│   ├── sales_analytics.sql
│   ├── ranking_analysis.sql
│   ├── purchase_trends.sql
│   ├── seller_review_analysis.sql
│   └── advanced_business_queries.sql
│
├── screenshots
│   ├── database_schema.png
│   └── query_results.png
│
└── README.md
