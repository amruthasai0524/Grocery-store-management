Overview:
This project designs and analyzes a complete SQL database for a grocery store, covering customers, products, categories, suppliers, employees, orders, and order details. It focuses on clean relational modeling and business-driven queries that mirror real-world retail analytics scenarios.​

What this project demonstrates
End-to-end relational design with primary keys, foreign keys, and enforced referential integrity between all core entities.​

Practical business questions answered with SQL: customer insights, product performance, sales trends, supplier contribution, and employee productivity.​

Writing optimized aggregate queries for revenue, quantity, frequency, and trend-based metrics across multiple joined tables.​

**Data model highlights:**
Core tables: customers, orders, orderdetails, products, categories, suppliers, store_employees.​

Strong constraints: primary keys on all ID fields and foreign keys linking orders to customers/employees, orderdetails to orders/products, and products to categories/suppliers.​

Structure supports extensibility for inventory, discounts, loyalty programs, and store branches.

**Key analytics included**:
Customer analytics: unique customers, high-frequency buyers, total and average purchase value per customer, top 5 revenue-generating customers.​

Product & category performance: products per category, average price by category, quantity sold and revenue per product, category–supplier level performance.​

Sales trends: total orders, average order value, high-traffic dates, monthly revenue trends, weekday vs weekend behavior.​

Supplier contribution: number of products per supplier, average price by supplier, revenue contribution per supplier.​

Employee performance: number of employees processing orders, orders handled per employee, total and average sales value handled per employee.​

**How to run:**
Create a database and select it:

**sql:**
CREATE DATABASE project;
USE project;
Run file-project.sql in your SQL client (e.g., MySQL Workbench, DBeaver) to create tables, constraints, and analysis queries.​

Insert your own test data or connect to a transactional source, then execute the analytical queries section-wise (Customer, Product, Sales, Supplier, Employee).​

Tech stack
SQL (MySQL-compatible)

Relational database design and analytics

Focus on query-writing, not UI, to highlight data modeling and analysis skills.
