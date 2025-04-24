

# Task 3: SQL for Data Analysis

## Objective

This task involves writing and executing SQL queries to extract insights from an e-commerce-style dataset using PostgreSQL. The goal was to apply SQL concepts like filtering, joins, aggregations, subqueries, views, and indexing.

---

## 🛠️ Tools Used

- [DB Fiddle (PostgreSQL v15)](https://www.db-fiddle.com/)
- PostgreSQL dialect
- Browser-based environment (no local installation needed)

---

## Dataset Structure

### `customers`
| Column       | Type          |
|--------------|---------------|
| customer_id  | SERIAL PRIMARY KEY |
| name         | VARCHAR(100)  |
| country      | VARCHAR(50)   |

### `orders`
| Column       | Type              |
|--------------|-------------------|
| order_id     | SERIAL PRIMARY KEY |
| customer_id  | INT (FK to customers) |
| order_date   | DATE              |
| total_amount | DECIMAL(10, 2)    |

---

## SQL Concepts Used

1. **Basic Queries:**
   ```sql
   SELECT * FROM customers;
   SELECT * FROM orders;
