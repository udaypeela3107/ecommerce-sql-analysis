# Ecommerce Database Analysis using PostgreSQL

## Project Overview

This project analyzes the Brazilian Olist Ecommerce Dataset using PostgreSQL.

The objective was to build a relational database, import raw CSV files, establish relationships using primary and foreign keys, generate an ER diagram, and perform business analytics using SQL queries.

---

## Dataset Information

Dataset: Olist Brazilian Ecommerce Dataset

Tables Used:

* Customers
* Orders
* Order Items
* Products
* Sellers
* Payments
* Reviews
* Category Translation

Total Orders: 99,441

---

## Technologies Used

* PostgreSQL
* pgAdmin 4
* SQL
* GitHub

---

## Database Schema

The database was normalized into multiple related tables.

### Main Relationships

* Customers → Orders
* Orders → Payments
* Orders → Reviews
* Orders → Order Items
* Products → Order Items
* Sellers → Order Items
* Categories → Products

ER Diagram:

(Add ER_Diagram.png after uploading)

---

## Analytics Performed

### 1. Total Orders Analysis

Purpose:
Determine the total number of orders placed.

Business Insight:
The platform processed more than 99,000 orders, indicating large-scale ecommerce activity.

### 2. Revenue by Payment Type

Purpose:
Identify the most commonly used payment methods and revenue contribution.

Business Insight:
Certain payment methods contribute significantly more revenue than others.

### 3. Top Selling Products

Purpose:
Find products with the highest sales volume.

Business Insight:
A small group of products drives a large portion of sales.

### 4. Orders by State

Purpose:
Analyze geographic distribution of customers.

Business Insight:
Customer demand is concentrated in specific states.

### 5. Average Payment Value

Purpose:
Measure average customer spending per transaction.

Business Insight:
Provides understanding of customer purchasing behavior.

### 6. Top Sellers

Purpose:
Identify highest-performing sellers.

Business Insight:
Top sellers contribute a substantial portion of marketplace sales.

---

## Key SQL Concepts Used

* SELECT
* JOIN
* GROUP BY
* ORDER BY
* Aggregate Functions
* Primary Keys
* Foreign Keys
* Data Normalization

---

## Conclusion

This project demonstrates database design, data modeling, SQL querying, relationship management, and business analytics using PostgreSQL. The project showcases practical skills required for Data Analyst and SQL Developer roles.
