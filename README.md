# Introduction to SQL: Practice & Portfolio Projects

A comprehensive collection of hands-on database queries, data analysis workflows, and practical mini-projects completed during my SQL training. 

This repository highlights intermediate relational database management, multi-table data modeling, aggregations, and business metrics reporting using **SQLite**.

## 📌 Featured Projects

### 1. Subscription Revenue Report
- **Goal:** Analyze revenue streams generated across different subscription packages.
- **Key Techniques:** Joined `subscriptions` metadata with `orders` records and applied `SUM()` aggregate functions grouped by subscription type.
- **Key Insight:** Identified high-performing subscription tiers to evaluate overall business growth.

### 2. Top Customer Identification
- **Goal:** Isolate high-value repeat buyers to target for loyalty programs.
- **Key Techniques:** Performed multi-table joins across `customers` and `orders`, aggregated total order counts with `COUNT()`, and filtered grouped datasets using the `HAVING` clause (`HAVING COUNT(orders.order_id) > 1`).

## 🛠️ Key SQL Concepts Mastered

- **Data Inspection:** Inspecting schema structures using SQLite PRAGMA utilities (`PRAGMA table_info`).
- **Multi-Table Joins:** Linking primary and foreign keys using `INNER JOIN`, `LEFT JOIN` (preserving unmatched records), and bridge/junction table navigation.
- **Set Operations & Combination:** Combining dataset outputs with `CROSS JOIN` (Cartesian products) and `UNION`.
- **Common Table Expressions (CTEs):** Writing modular, readable subquery logic using `WITH` statements.
- **Data Filtering & Aggregations:** Analyzing metrics using `SUM()`, `COUNT()`, `GROUP BY`, and mastering the execution order difference between `WHERE` (row-level filtering) and `HAVING` (group-level filtering).

## 🧰 Tech Stack
- **Database Engine:** SQLite
- **Query Language:** SQL
- **Version Control:** Git & GitHub
