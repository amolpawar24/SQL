# SQL

A complete SQL learning repository covering **SQL fundamentals, database concepts, CRUD operations, querying, functions, joins, subqueries, constraints, database design, transactions, views, indexes, stored procedures, triggers, optimization, and advanced SQL concepts**.

> **Learn • Practice • Build**

---

# 📚 Complete SQL Syllabus

## 01. Database Fundamentals

* What is Data?
* What is a Database?
* What is DBMS?
* What is RDBMS?
* DBMS vs RDBMS
* What is SQL?
* SQL Features
* SQL Advantages
* SQL Limitations
* SQL Standards
* SQL vs NoSQL
* Relational Database Concepts
* Tables
* Rows
* Columns
* Records
* Fields
* Relationships
* Schema
* Database Objects

---

## 02. SQL Environment & Tools

* Installing MySQL
* Installing MySQL Workbench
* MySQL Server
* MySQL Client
* Connecting to MySQL
* Creating a Database
* Selecting a Database
* Viewing Databases
* Viewing Tables
* Viewing Table Structure
* SQL Comments
* SQL Statements
* SQL Syntax
* SQL Naming Conventions

---

## 03. SQL Data Types

### Numeric Data Types

* INT
* SMALLINT
* MEDIUMINT
* BIGINT
* DECIMAL
* NUMERIC
* FLOAT
* DOUBLE

### String Data Types

* CHAR
* VARCHAR
* TEXT
* TINYTEXT
* MEDIUMTEXT
* LONGTEXT

### Date & Time Data Types

* DATE
* TIME
* DATETIME
* TIMESTAMP
* YEAR

### Other Data Types

* BOOLEAN
* JSON
* ENUM
* SET
* BLOB

---

## 04. Database & Table Management

### Database Commands

* CREATE DATABASE
* DROP DATABASE
* ALTER DATABASE
* USE DATABASE
* SHOW DATABASES

### Table Commands

* CREATE TABLE
* DROP TABLE
* ALTER TABLE
* RENAME TABLE
* TRUNCATE TABLE
* DESCRIBE TABLE
* SHOW TABLES

### ALTER TABLE

* ADD COLUMN
* MODIFY COLUMN
* CHANGE COLUMN
* DROP COLUMN
* RENAME COLUMN

---

## 05. SQL Constraints

* What are Constraints?
* NOT NULL
* UNIQUE
* PRIMARY KEY
* FOREIGN KEY
* CHECK
* DEFAULT
* AUTO_INCREMENT

### Keys

* Primary Key
* Foreign Key
* Candidate Key
* Super Key
* Alternate Key
* Composite Key
* Natural Key
* Surrogate Key

---

## 06. CRUD Operations

### CREATE

* INSERT
* INSERT Single Row
* INSERT Multiple Rows

### READ

* SELECT
* SELECT Specific Columns
* SELECT All Columns
* DISTINCT

### UPDATE

* UPDATE
* Updating Single Column
* Updating Multiple Columns
* Updating Multiple Rows

### DELETE

* DELETE
* DELETE Specific Rows
* DELETE Multiple Rows

### TRUNCATE vs DELETE vs DROP

---

## 07. SELECT Queries

* SELECT
* FROM
* DISTINCT
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* LIMIT
* OFFSET
* Aliases
* Column Aliases
* Table Aliases

---

## 08. SQL Operators

### Arithmetic Operators

* *
* *
* *
* /
* %

### Comparison Operators

* =
* !=
* <>
* >
* <
* > =
* <=

### Logical Operators

* AND
* OR
* NOT

### Special Operators

* BETWEEN
* IN
* NOT IN
* LIKE
* NOT LIKE
* IS NULL
* IS NOT NULL
* EXISTS
* NOT EXISTS

---

## 09. SQL Filtering

* WHERE Clause
* AND
* OR
* NOT
* BETWEEN
* IN
* NOT IN
* LIKE
* Wildcards
* `%`
* `_`
* NULL Values
* IS NULL
* IS NOT NULL

---

## 10. Sorting & Pagination

* ORDER BY
* ASC
* DESC
* LIMIT
* OFFSET
* Pagination
* Top-N Queries

---

## 11. SQL Functions

### Aggregate Functions

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

### String Functions

* CONCAT()
* CONCAT_WS()
* LENGTH()
* CHAR_LENGTH()
* LOWER()
* UPPER()
* TRIM()
* LTRIM()
* RTRIM()
* SUBSTRING()
* LEFT()
* RIGHT()
* REPLACE()
* REVERSE()
* LOCATE()
* INSTR()

### Numeric Functions

* ROUND()
* CEIL()
* FLOOR()
* ABS()
* MOD()
* POWER()
* SQRT()
* RAND()

### Date & Time Functions

* NOW()
* CURDATE()
* CURTIME()
* CURRENT_DATE()
* CURRENT_TIME()
* CURRENT_TIMESTAMP()
* DATE()
* TIME()
* YEAR()
* MONTH()
* DAY()
* HOUR()
* MINUTE()
* SECOND()
* DATE_FORMAT()
* DATEDIFF()
* TIMESTAMPDIFF()
* DATE_ADD()
* DATE_SUB()

### Conditional Functions

* IF()
* IFNULL()
* NULLIF()
* COALESCE()
* CASE
* WHEN
* THEN
* ELSE
* END

---

## 12. NULL Handling

* What is NULL?
* NULL vs 0
* NULL vs Empty String
* IS NULL
* IS NOT NULL
* IFNULL()
* COALESCE()
* NULLIF()

---

## 13. GROUP BY & HAVING

* GROUP BY
* Aggregate Functions with GROUP BY
* Multiple Columns in GROUP BY
* HAVING
* WHERE vs HAVING
* GROUP BY with ORDER BY
* GROUP BY with LIMIT

---

## 14. SQL Joins

### Basic Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN

### Advanced Joins

* CROSS JOIN
* SELF JOIN
* NATURAL JOIN

### Join Concepts

* Joining Two Tables
* Joining Multiple Tables
* Join Conditions
* ON vs WHERE
* INNER JOIN vs OUTER JOIN
* LEFT JOIN vs RIGHT JOIN

---

## 15. Subqueries

* What is a Subquery?
* Single-Row Subquery
* Multiple-Row Subquery
* Multiple-Column Subquery
* Scalar Subquery
* Correlated Subquery
* Nested Subquery
* Subquery with SELECT
* Subquery with WHERE
* Subquery with FROM
* Subquery with HAVING
* Subquery with INSERT
* Subquery with UPDATE
* Subquery with DELETE

### Subquery Operators

* IN
* NOT IN
* EXISTS
* NOT EXISTS
* ANY
* ALL

---

## 16. Set Operations

* UNION
* UNION ALL
* INTERSECT
* EXCEPT
* Set Operation Rules
* UNION vs UNION ALL

> Note: Set-operation support can vary by database system.

---

## 17. Common Table Expressions

* What is CTE?
* WITH Clause
* Simple CTE
* Multiple CTEs
* CTE with JOIN
* CTE with Aggregate Functions
* CTE vs Subquery
* Recursive CTE
* Recursive Queries

---

## 18. SQL Views

* What is a View?
* CREATE VIEW
* SELECT from View
* UPDATE View
* DROP VIEW
* CREATE OR REPLACE VIEW
* Advantages of Views
* Limitations of Views
* Views vs Tables

---

## 19. SQL Indexes

* What is an Index?
* Why Indexes are Used
* CREATE INDEX
* DROP INDEX
* UNIQUE INDEX
* Composite Index
* Clustered Index
* Non-Clustered Index
* Index Selection
* Index Advantages
* Index Disadvantages
* Indexing Best Practices

---

## 20. Database Relationships

* One-to-One
* One-to-Many
* Many-to-Many
* Primary Key Relationships
* Foreign Key Relationships
* Junction / Bridge Tables
* Referential Integrity
* Cascading Relationships

### Foreign Key Actions

* ON DELETE CASCADE
* ON DELETE SET NULL
* ON DELETE RESTRICT
* ON UPDATE CASCADE

---

## 21. Database Normalization

* What is Normalization?
* Why Normalize a Database?
* Data Redundancy
* Data Anomalies
* Insert Anomaly
* Update Anomaly
* Delete Anomaly

### Normal Forms

* First Normal Form (1NF)
* Second Normal Form (2NF)
* Third Normal Form (3NF)
* Boyce-Codd Normal Form (BCNF)
* Fourth Normal Form (4NF)
* Fifth Normal Form (5NF)

### Denormalization

* What is Denormalization?
* Advantages
* Disadvantages
* Normalization vs Denormalization

---

## 22. Transactions

* What is a Transaction?
* Transaction Lifecycle
* COMMIT
* ROLLBACK
* SAVEPOINT
* ROLLBACK TO SAVEPOINT
* RELEASE SAVEPOINT

### ACID Properties

* Atomicity
* Consistency
* Isolation
* Durability

---

## 23. Transaction Isolation

* Read Uncommitted
* Read Committed
* Repeatable Read
* Serializable

### Transaction Problems

* Dirty Read
* Non-Repeatable Read
* Phantom Read
* Lost Update

---

## 24. Stored Procedures

* What is a Stored Procedure?
* CREATE PROCEDURE
* CALL
* DROP PROCEDURE
* Procedure Parameters
* IN Parameter
* OUT Parameter
* INOUT Parameter
* Variables
* Conditional Statements
* Loops
* Stored Procedure Examples

---

## 25. SQL Functions

* What is a User-Defined Function?
* CREATE FUNCTION
* Function Parameters
* RETURN
* Calling Functions
* DROP FUNCTION
* Stored Procedure vs Function

---

## 26. Triggers

* What is a Trigger?
* BEFORE INSERT
* AFTER INSERT
* BEFORE UPDATE
* AFTER UPDATE
* BEFORE DELETE
* AFTER DELETE
* CREATE TRIGGER
* DROP TRIGGER
* Trigger Use Cases
* Trigger Advantages
* Trigger Limitations

---

## 27. Cursors

* What is a Cursor?
* Cursor Declaration
* OPEN Cursor
* FETCH
* CLOSE Cursor
* Cursor Variables
* Cursor with Stored Procedures
* Cursor Use Cases

---

## 28. Temporary Tables

* What is a Temporary Table?
* CREATE TEMPORARY TABLE
* Temporary Table Usage
* Temporary Table vs Permanent Table
* DROP TEMPORARY TABLE

---

## 29. SQL Security

* Database Users
* CREATE USER
* DROP USER
* ALTER USER
* GRANT
* REVOKE
* Roles
* Privileges
* Authentication
* Authorization

---

## 30. SQL Performance Optimization

* Query Performance
* Query Execution
* Query Optimization
* Index Optimization
* Avoiding Unnecessary SELECT *
* Efficient WHERE Conditions
* Efficient JOINs
* Query Optimization Techniques
* Database Statistics
* Execution Plans

### EXPLAIN

* EXPLAIN
* Reading Execution Plans
* Full Table Scans
* Index Usage
* Query Cost

---

## 31. Advanced SQL

* Window Functions
* Ranking Functions
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* NTILE()
* LEAD()
* LAG()
* FIRST_VALUE()
* LAST_VALUE()
* PARTITION BY
* Window Frames

---

## 32. Advanced Query Techniques

* Conditional Aggregation
* Running Totals
* Moving Averages
* Ranking Records
* Finding Duplicates
* Removing Duplicates
* Finding Second Highest Salary
* Top-N Records
* Gaps and Islands
* Pivoting Data
* Unpivoting Data
* Recursive Queries
* Hierarchical Data

---

## 33. Database Design

* Database Design Principles
* Entity
* Attribute
* Relationship
* Entity Relationship Model
* ER Diagrams
* Cardinality
* Primary Keys
* Foreign Keys
* Composite Keys
* Database Schema Design
* Relational Modeling

---

## 34. SQL Data Import & Export

* Importing SQL Files
* Exporting Databases
* Database Backup
* Database Restore
* CSV Import
* CSV Export
* Data Migration
* mysqldump
* mysql Command-Line Client

---

## 35. SQL with Application Development

* SQL with Java
* SQL with JDBC
* SQL with Spring Boot
* SQL with Node.js
* SQL with Express.js
* SQL with Python
* SQL with Django
* SQL with REST APIs
* CRUD Application with SQL
* Database Connection
* Connection Pooling
* Prepared Statements
* Parameterized Queries

---

## 36. SQL Security & Best Practices

* SQL Injection
* Parameterized Queries
* Prepared Statements
* Input Validation
* Least Privilege
* Secure Database Credentials
* Environment Variables
* Password Security
* Database Access Control

---

## 37. Real-World Database Projects

### Beginner Projects

* Student Database
* Employee Database
* Library Database
* Product Database
* Hospital Database

### Intermediate Projects

* E-Commerce Database
* Banking Database
* Hotel Management Database
* Inventory Management Database
* Employee Management System

### Advanced Projects

* E-Commerce Order Management
* Banking Transaction System
* Food Delivery Database
* Learning Management System
* Job Portal Database
* Social Media Database

---

## 38. SQL Practice

* Basic SQL Questions
* SELECT Practice
* WHERE Practice
* GROUP BY Practice
* HAVING Practice
* JOIN Practice
* Subquery Practice
* Function Practice
* CTE Practice
* Window Function Practice
* Database Design Practice
* Real-World Query Problems

---

## 39. SQL Interview Preparation

### Basic Questions

* What is SQL?
* What is DBMS?
* What is RDBMS?
* What is a Primary Key?
* What is a Foreign Key?
* What is a Constraint?
* What is NULL?

### Intermediate Questions

* DELETE vs TRUNCATE vs DROP
* WHERE vs HAVING
* UNION vs UNION ALL
* Primary Key vs Unique Key
* CHAR vs VARCHAR
* JOIN vs Subquery
* Indexes
* Normalization
* Transactions
* ACID Properties

### Advanced Questions

* CTE vs Subquery
* Window Functions
* Clustered vs Non-Clustered Index
* Transaction Isolation
* Deadlocks
* Query Optimization
* Execution Plans
* Stored Procedures
* Functions vs Procedures
* Triggers
* Database Design

---

# 📁 Repository Structure

```text
SQL/
│
├── 01-Database-Fundamentals/
├── 02-SQL-Environment/
├── 03-Data-Types/
├── 04-Database-Table-Management/
├── 05-Constraints/
├── 06-CRUD-Operations/
├── 07-SELECT-Queries/
├── 08-Operators/
├── 09-Filtering/
├── 10-Sorting-Pagination/
├── 11-Functions/
├── 12-NULL-Handling/
├── 13-GROUP-BY-HAVING/
├── 14-Joins/
├── 15-Subqueries/
├── 16-Set-Operations/
├── 17-CTE/
├── 18-Views/
├── 19-Indexes/
├── 20-Relationships/
├── 21-Normalization/
├── 22-Transactions/
├── 23-Transaction-Isolation/
├── 24-Stored-Procedures/
├── 25-SQL-Functions/
├── 26-Triggers/
├── 27-Cursors/
├── 28-Temporary-Tables/
├── 29-SQL-Security/
├── 30-Performance-Optimization/
├── 31-Advanced-SQL/
├── 32-Advanced-Queries/
├── 33-Database-Design/
├── 34-Import-Export/
├── 35-SQL-Application-Development/
├── 36-Security-Best-Practices/
├── 37-Projects/
├── 38-Practice/
└── 39-Interview-Preparation/
```

---

# 🛠️ Tools & Technologies

* SQL
* MySQL
* MySQL Workbench
* Git
* GitHub

---

# 🎯 Learning Goals

* Build strong SQL fundamentals
* Understand relational databases
* Write efficient SQL queries
* Work with multiple related tables
* Understand database design
* Master joins and subqueries
* Learn advanced SQL techniques
* Understand transactions and ACID
* Optimize database queries
* Build real-world database projects
* Prepare for SQL interviews
* Use SQL with backend applications

---

# 📈 Learning Progress

| Section                  | Status |
| ------------------------ | ------ |
| Database Fundamentals    | ⬜      |
| SQL Environment          | ⬜      |
| Data Types               | ⬜      |
| Table Management         | ⬜      |
| Constraints              | ⬜      |
| CRUD Operations          | ⬜      |
| SELECT Queries           | ⬜      |
| Operators                | ⬜      |
| Filtering                | ⬜      |
| Sorting & Pagination     | ⬜      |
| Functions                | ⬜      |
| GROUP BY & HAVING        | ⬜      |
| Joins                    | ⬜      |
| Subqueries               | ⬜      |
| Set Operations           | ⬜      |
| CTE                      | ⬜      |
| Views                    | ⬜      |
| Indexes                  | ⬜      |
| Relationships            | ⬜      |
| Normalization            | ⬜      |
| Transactions             | ⬜      |
| Stored Procedures        | ⬜      |
| Functions                | ⬜      |
| Triggers                 | ⬜      |
| Cursors                  | ⬜      |
| Security                 | ⬜      |
| Performance Optimization | ⬜      |
| Advanced SQL             | ⬜      |
| Database Design          | ⬜      |
| Projects                 | ⬜      |
| Practice                 | ⬜      |
| Interview Preparation    | ⬜      |

---

# 👨‍💻 Author

**Amol Pawar**

GitHub: [@amolpawar24](https://github.com/amolpawar24)

---

## ⭐ Repository

This repository is continuously updated as I learn and practice SQL concepts.

If you find it useful, consider giving the repository a ⭐.
