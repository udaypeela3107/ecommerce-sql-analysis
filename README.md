# Ecommerce Database Analysis using PostgreSQL

## Project Overview
This project analyzes an Ecommerce dataset using PostgreSQL.

The project includes:

- Data Import and Cleaning
- Database Design
- Primary and Foreign Key Relationships
- ER Diagram Creation
- SQL Analytics Queries
- Business Insights

---

## Dataset Information

Dataset: Brazilian Ecommerce Dataset (Olist)

Tables Used:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Categories

---

## Database Schema

Primary Keys:
- customer_id
- order_id
- product_id
- seller_id

Foreign Keys:
- orders.customer_id → customers.customer_id
- payments.order_id → orders.order_id
- order_items.order_id → orders.order_id
- order_items.product_id → products.product_id
- order_items.seller_id → sellers.seller_id

---

## ER Diagram

See ER_Diagram.png

---

## Analytics Performed

1. Total Orders
2. Revenue by Payment Type
3. Top Selling Products
4. Orders by State
5. Average Payment Value
6. Top Sellers

Screenshots available in Analytics folder.

---

## Tools Used

- PostgreSQL
- pgAdmin 4
- SQL
- GitHub

---

## Author

Uday Kumar Peela
