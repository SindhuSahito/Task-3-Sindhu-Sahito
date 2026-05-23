# Task-3-Sindhu-Sahito
SQL Data Analysis Project – E-Commerce Orders

This project focuses on analyzing an e-commerce orders dataset using SQL queries. The purpose of this project is to learn and practice important SQL concepts such as filtering, grouping, aggregation, sorting, and revenue analysis.

The dataset contains information about customer orders, products, payment methods, referral sources, and total sales.

Tools Used

SQLite / DuckDB
SQL
Google Colab
CSV Dataset
Dataset Columns
OrderID
Date
CustomerID
Product
Quantity
UnitPrice
PaymentMethod
OrderStatus
TrackingNumber
ItemsInCart
CouponCode
ReferralSource
TotalPrice

SQL Concepts Used

SELECT
WHERE
GROUP BY
COUNT()
SUM()
AVG()
ORDER BY
LIMIT
Date Functions
Aliases

Tasks Performed

Filtered high-value orders
Analyzed delivered and shipped orders
Counted orders per product
Calculated revenue by payment method
Found average order value by referral source
Identified top-selling products
Analyzed monthly revenue trends
Compared COUNT(*) and COUNT(column)
Understood SQL alias trap and execution order

Sample Query

SELECT Product,
       SUM(Quantity) AS TotalSold
FROM orders
GROUP BY Product
ORDER BY TotalSold DESC
LIMIT 5;

Key Learnings

How SQL is used for business analysis
How to summarize and group data
How aggregate functions work
Importance of SQL execution order
Basic revenue and sales analysis techniques

Conclusion
This project helped in understanding practical SQL data analysis using an e-commerce dataset. It improved knowledge of querying, filtering, grouping, and generating business insights from data.
