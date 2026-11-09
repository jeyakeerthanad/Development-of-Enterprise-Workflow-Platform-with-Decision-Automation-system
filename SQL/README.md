# SQL Practice – Retail Sales Analysis

## Project Overview

This project focuses on practising SQL queries using a Retail Sales database. It consists of 10 SQL problems designed to demonstrate different SQL concepts through practical examples.

## Tools Used

- MySQL 8.0
- Python
- Google Colab
- IPython-SQL (`ipython-sql`, `pymysql`)

## Database Schema

**Database:** `RetailDB` | **Table:** `Sales`

| Column | Data Type | Description |
|---|---|---|
| `sale_id` | INT (Primary Key) | Unique sale identifier |
| `product_name` | VARCHAR(50) | Name of the product |
| `category` | VARCHAR(50) | Product category |
| `quantity` | INT | Units sold |
| `price` | DECIMAL(10,2) | Price per unit |
| `city` | VARCHAR(50) | City where the sale occurred |
| `sale_date` | DATE | Date of sale |

The table contains 10 sample records across Electronics, Fashion, and Accessories categories in four cities: Chennai, Madurai, Salem, and Coimbatore.

## Concepts Covered
- Aggregate Functions (`COUNT`, `SUM`, `MAX`)
- `GROUP BY` and `HAVING`
- `ORDER BY`
- `WHERE` Clause
- `DISTINCT`
- `LIKE` and `IN` Operators
- Subqueries
- `CASE` Statements

## Project Structure

- `SQL_Task.ipynb` – Contains the problem statements, natural-language prompts, SQL queries, and execution outputs.

## How to Run

1. Download or clone this repository.
2. Open `SQL_Task.ipynb` in Google Colab or a Jupyter environment (Ubuntu/Debian).
3. Run the cells in order. The notebook installs and starts MySQL, creates the database and table, inserts the sample data, and executes the queries.
4. The notebook uses sample MySQL credentials (`root` / `root`). Replace them with your own credentials if needed.

## Objective

To develop practical SQL querying skills and understand how SQL can be used to retrieve, filter, group, and analyse data from a relational database.
