# SQL Learning Repository

## Overview
This repository contains a comprehensive set of SQL exercises designed to build strong foundations in database design, querying, and optimization. The tasks progress from basic table operations to advanced topics like window functions, transactions, and database architecture.

The goal is to simulate real-world database scenarios used in backend systems such as eCommerce platforms, analytics pipelines, and enterprise applications.

---

## Objectives

- Understand relational database concepts
- Write efficient and optimized SQL queries
- Design normalized database schemas
- Perform data analysis using SQL
- Handle transactions and maintain data integrity
- Implement advanced SQL features like CTEs, window functions, and triggers

---

## Topics Covered

### 1. Table Creation and Data Insertion
- CREATE TABLE
- Data types and constraints
- INSERT INTO
- Basic SELECT queries

### 2. Filtering and Sorting
- WHERE clause
- Logical operators (AND, OR)
- ORDER BY (ASC, DESC)

### 3. Aggregation and Grouping
- COUNT, SUM, AVG
- GROUP BY
- HAVING clause

### 4. Joins and Relationships
- INNER JOIN, LEFT JOIN, RIGHT JOIN
- Foreign keys
- Relational data modeling

### 5. Subqueries
- Nested queries
- Correlated vs non-correlated subqueries
- EXISTS and IN

### 6. Date and Time Functions
- DATEADD, DATEDIFF
- Filtering by date ranges
- Date formatting

### 7. Window Functions
- ROW_NUMBER, RANK, DENSE_RANK
- PARTITION BY
- LEAD and LAG

### 8. Common Table Expressions (CTEs)
- Non-recursive CTEs
- Recursive queries
- Hierarchical data processing

### 9. Stored Procedures and Functions
- Parameterized procedures
- Scalar and table-valued functions
- Encapsulation of business logic

### 10. Advanced Database Design
- Normalization
- Indexing strategies
- Triggers
- Transactions (ACID properties)
- Views

---

## Repository Structure

Each task is organized as:

sql/task-x/

Each task contains:

- `commands.txt` → SQL queries and explanations
- Structured steps for execution

---

## Key Concepts

### Relational Model
- Data is stored in tables (relations)
- Relationships are defined using primary and foreign keys

### Normalization
- Eliminates redundancy
- Improves data integrity

### Query Execution Order
FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY

### Indexing
- Improves read performance
- Should be used carefully due to write overhead

---

## Best Practices

- Use meaningful table and column names
- Normalize schema to reduce redundancy
- Use indexes on frequently queried columns
- Avoid unnecessary subqueries; prefer joins when possible
- Handle NULL values carefully
- Use transactions for critical operations
- Write readable and maintainable queries

---

## Common Pitfalls

- Using WHERE instead of HAVING for aggregates
- Overusing SELECT *
- Ignoring indexes
- Writing inefficient correlated subqueries
- Not handling transactions properly

---

## Real-World Applications

- eCommerce systems (orders, products, customers)
- Banking systems (transactions, accounts)
- Analytics dashboards
- Backend APIs

---

## Tools Used

- SQL Server / MySQL / PostgreSQL (dialect variations noted)
- Command-line or GUI tools (SSMS, MySQL Workbench, pgAdmin)
