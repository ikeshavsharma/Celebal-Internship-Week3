# Superstore Sales Analysis Using SQL

## Celebal Summer Internship 2026 - Week 3 Assignment

### Objective

The objective of this assignment is to analyze Superstore sales data using SQL by applying:

* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Joins

The project focuses on extracting meaningful business insights from sales transactions and customer purchasing behavior.

---

## Dataset

**Dataset:** Sample Superstore Dataset

The dataset contains information related to:

* Customers
* Orders
* Products
* Sales
* Profit
* Discounts
* Regions

---

## Database Design

The raw dataset was imported into:

```sql
superstore_raw
```

The dataset was further normalized into the following tables:

* customers
* products
* orders

Data was inserted into these tables using `SELECT DISTINCT`.

---

## SQL Concepts Used

### Subqueries

* Orders with sales above average sales
* Highest sales order for each customer

### Common Table Expressions (CTEs)

* Total sales calculation per customer
* Customers with above-average sales

### Window Functions

* RANK()
* ROW_NUMBER()
* PARTITION BY

### Combined Analysis

* JOIN + CTE + Window Function
* Customer sales ranking

---

## Business Questions Solved

1. Who are the top 5 customers?
2. Who are the bottom 5 customers?
3. Which customers placed only one order?
4. Which customers have above-average sales?
5. What is the highest order value per customer?

---

## Key Findings

* A small group of customers contributes a significant portion of total sales.
* Customer SM-20320 generated the highest total sales.
* Several customers generated sales far above the average customer sales value.
* High-value transactions have a major impact on overall revenue.
* Customer purchasing behavior varies significantly across the dataset.

---

## Files Included

| File                 | Description                                 |
| -------------------- | ------------------------------------------- |
| queries.sql          | Complete SQL queries used in the assignment |
| Week3_Report.pdf     | Query explanations and output screenshots   |
| Insights.md          | Business insights derived from the analysis |

---

## Technologies Used

* Microsoft SQL Server
* SQL Server Management Studio (SSMS)
* GitHub

---

## Author

**Keshav Sharma**

Celebal Summer Internship 2026
