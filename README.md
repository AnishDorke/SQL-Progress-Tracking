# SQL Progress Tracking & Learning Portfolio

A dedicated repository to track, document, and showcase my SQL learning journey, practical exercises, problem-solving skills, and proof of work across various open-source learning platforms and resources.

## About This Repository

This repository serves as a centralized record of my SQL learning progress and hands-on practice. It documents the concepts I learn, problems I solve, approaches I develop, and practical experience I gain while working with relational databases.

My learning journey includes practicing SQL through various platforms, coding challenges, documentation, and tutorials, with a focus on developing strong SQL fundamentals and advanced querying skills for data analytics and problem-solving.

This repository aims to:

- Track my progress from SQL fundamentals to advanced concepts.
- Document solved SQL problems and their solutions.
- Maintain screenshots and proof of completed exercises.
- Practice SQL across different platforms and learning resources.
- Develop logical thinking and SQL problem-solving patterns.
- Prepare for SQL interviews and data analyst roles.
- Build practical experience with MySQL and PostgreSQL.
- Create a structured portfolio showcasing my continuous learning.

## Learning Platforms & Resources

I use a combination of interactive platforms, coding challenges, tutorials, and documentation to strengthen my SQL knowledge.

| Platform / Resource | Purpose |
|---|---|
| [DataLemur](https://datalemur.com/) | SQL interview questions and analytical problem-solving |
| [StrataScratch](https://www.stratascratch.com/) | Real-world SQL interview questions |
| [HackerRank](https://www.hackerrank.com/domains/sql) | SQL fundamentals and coding challenges |
| [LeetCode](https://leetcode.com/problemset/database/) | SQL problem-solving and interview preparation |
| [SQL-Practice.com](https://www.sql-practice.com/) | Hands-on SQL practice using relational databases |
| [SQLBolt](https://sqlbolt.com/) | Interactive SQL lessons and exercises |
| [SQLNest](https://sqlnest.com/) | SQL learning and practice |
| YouTube Tutorials | Concept explanations, demonstrations, and guided exercises |
| Official Documentation | MySQL and PostgreSQL reference and documentation |

*Additional learning resources may be included as my learning journey progresses.*

## Technologies & Databases

### SQL Languages

- MySQL
- PostgreSQL

### Database Concepts

- Relational Database Management Systems (RDBMS)
- Tables, rows, and columns
- Primary keys and foreign keys
- Relationships between tables
- Database schemas
- Constraints and data integrity
- Normalization and denormalization
- Indexing and query performance

## SQL Learning Roadmap & Concepts

The following roadmap represents the concepts and skills I aim to learn and practice throughout this journey.

### 1. SQL Fundamentals
- Introduction to SQL and RDBMS
- Database, schema, table, row, and column
- SELECT statements
- DISTINCT
- Column aliases (AS)
- Arithmetic expressions
- NULL values
- Basic SQL syntax and query execution order

### 2. Filtering and Sorting
- WHERE clause
- AND, OR, NOT operators
- Comparison operators
- BETWEEN and NOT BETWEEN
- IN and NOT IN
- LIKE and NOT LIKE
- Wildcards (% and _)
- IS NULL and IS NOT NULL
- ORDER BY
- ASC and DESC
- LIMIT and OFFSET
- FETCH FIRST
- TOP (where supported)

### 3. Aggregate Functions
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()
- GROUP BY
- HAVING
- DISTINCT with aggregate functions
- Conditional aggregation
- Grouping by multiple columns

### 4. SQL Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- SELF JOIN
- Joining multiple tables
- Multiple join conditions
- Joining tables using primary and foreign keys
- Finding unmatched records
- Handling duplicate rows after joins

### 5. Subqueries
- Single-row subqueries
- Multiple-row subqueries
- Scalar subqueries
- Correlated subqueries
- Nested subqueries
- Subqueries in SELECT, FROM, and WHERE
- EXISTS and NOT EXISTS
- IN and NOT IN with subqueries
- ANY and ALL
- Subqueries with aggregate functions

### 6. Conditional Logic
- CASE WHEN
- ELSE and END
- Nested CASE statements
- Conditional aggregation
- IF() in MySQL
- COALESCE()
- NULLIF()
- IFNULL() in MySQL
- Conditional data categorization

### 7. Common Table Expressions (CTEs)
- WITH clause
- Basic CTEs
- Multiple CTEs
- CTE chaining
- CTEs with joins
- CTEs with aggregate functions
- Recursive CTEs
- CTEs versus subqueries

### 8. Window Functions
- Introduction to window functions
- OVER() clause
- PARTITION BY
- ORDER BY inside window functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- NTILE()
- LAG()
- LEAD()
- FIRST_VALUE()
- LAST_VALUE()
- NTH_VALUE()
- Running totals
- Moving averages
- Cumulative calculations
- Window frames (ROWS and RANGE)
- Ranking within groups
- Comparing current and previous rows

### 9. Set Operations
- UNION
- UNION ALL
- INTERSECT
- EXCEPT
- Combining results from multiple queries
- Understanding duplicate handling

### 10. String Functions
- CONCAT()
- CONCAT_WS()
- LENGTH() and CHAR_LENGTH()
- UPPER() and LOWER()
- TRIM(), LTRIM(), RTRIM()
- SUBSTRING()
- LEFT() and RIGHT()
- REPLACE()
- POSITION()
- LOCATE() in MySQL
- SPLIT_PART() in PostgreSQL
- String pattern matching
- Regular expressions

### 11. Date and Time Functions
- CURRENT_DATE
- CURRENT_TIME
- NOW()
- DATE()
- EXTRACT()
- YEAR(), MONTH(), DAY()
- DATE_ADD() and DATE_SUB() in MySQL
- INTERVAL operations
- AGE() in PostgreSQL
- DATE_TRUNC() in PostgreSQL
- DATEDIFF()
- Date comparisons
- Date formatting
- Date range filtering
- Working with timestamps and time zones

### 12. Mathematical and Numeric Functions
- ROUND()
- CEIL() / CEILING()
- FLOOR()
- ABS()
- MOD()
- POWER()
- SQRT()
- RAND() / RANDOM()
- Numeric calculations and percentage calculations

### 13. Data Definition Language (DDL)
- CREATE DATABASE
- CREATE TABLE
- ALTER TABLE
- DROP TABLE
- TRUNCATE TABLE
- RENAME TABLE
- Column data types
- Constraints
- Primary keys
- Foreign keys
- UNIQUE
- NOT NULL
- CHECK
- DEFAULT
- AUTO_INCREMENT in MySQL
- SERIAL and IDENTITY columns in PostgreSQL

### 14. Data Manipulation Language (DML)
- INSERT INTO
- INSERT multiple records
- UPDATE
- DELETE
- UPSERT
- INSERT ... ON DUPLICATE KEY UPDATE in MySQL
- INSERT ... ON CONFLICT in PostgreSQL
- Data modification using conditions
- RETURNING in PostgreSQL

### 15. Database Design & Management
- Relational database design
- Entity Relationship Diagrams (ERD)
- One-to-one relationships
- One-to-many relationships
- Many-to-many relationships
- Database normalization (1NF, 2NF, 3NF, BCNF)
- Denormalization
- Referential integrity
- Composite keys
- Candidate keys
- Surrogate keys
- Views and materialized views
- Temporary tables

### 16. Transactions and Advanced Database Concepts
- Transactions
- BEGIN / START TRANSACTION
- COMMIT
- ROLLBACK
- SAVEPOINT
- ACID properties
- Transaction isolation levels
- Locks and concurrency
- Deadlocks
- Stored procedures
- User-defined functions
- Triggers
- Cursors
- Permissions and access control

### 17. Indexing and Query Optimization
- Index fundamentals
- Clustered and non-clustered indexes (where supported)
- Single-column indexes
- Composite indexes
- Unique indexes
- B-tree indexes
- Hash indexes
- Partial indexes in PostgreSQL
- EXPLAIN
- EXPLAIN ANALYZE
- Query execution plans
- Index usage and selectivity
- Query optimization techniques
- Avoiding unnecessary scans and operations
- Understanding query performance

### 18. Advanced SQL Features
- JSON data types and functions
- JSON querying and manipulation
- Common Table Expressions
- Recursive queries
- Pivoting and unpivoting
- Conditional aggregation
- Lateral joins
- FULL TEXT search
- Regular expression queries
- Advanced analytical queries
- Generating reports using SQL

## SQL Problem-Solving Patterns

Along with learning individual SQL concepts, I aim to recognize and master commonly used SQL problem-solving patterns.

### Basic Query Patterns
- Filtering and sorting
- Aggregation and grouping
- Conditional aggregation
- Multiple table joins
- Finding distinct records
- Finding missing or NULL values
- Finding duplicate records
- Removing duplicate records
- Top N records
- Second-highest and Nth-highest values
- Minimum and maximum values per group

### Intermediate Patterns
- JOIN + GROUP BY
- Subquery-based filtering
- Correlated subqueries
- Self-join patterns
- EXISTS and NOT EXISTS
- Anti-joins
- Top N per group
- Ranking within categories
- Finding records above group averages
- Comparing records within groups
- Conditional counting
- Multiple-level aggregation
- Date-based grouping
- Consecutive records

### Advanced Patterns
- Window function ranking
- Running totals and cumulative sums
- Moving averages
- LAG and LEAD comparisons
- First and last record per group
- Gaps and islands
- Consecutive days or events
- Deduplication using ROW_NUMBER()
- Median and percentile calculations
- Cohort analysis
- Retention analysis
- Customer segmentation
- Customer lifetime value calculations
- Monthly and yearly growth
- Month-over-month (MoM) analysis
- Year-over-year (YoY) analysis
- Rolling time-window analysis
- Funnel analysis
- Sessionization
- Market basket analysis
- Recursive hierarchy queries
- Conditional ranking
- Complex multi-table analytical queries

### Business and Data Analytics Patterns
- Revenue and sales analysis
- Customer purchase behavior
- Product performance analysis
- Order and transaction analysis
- Employee and department analysis
- Customer retention and churn
- Repeat purchase analysis
- Conversion rate calculations
- Running and cumulative metrics
- Percentage contribution
- Ranking products and customers
- Identifying business trends
- KPI calculations

## MySQL vs PostgreSQL

I will practice using both MySQL and PostgreSQL to understand their syntax, features, similarities, and differences.

| Area | MySQL | PostgreSQL |
|---|---|---|
| Auto-generated IDs | AUTO_INCREMENT | IDENTITY / SERIAL |
| String concatenation | CONCAT() | CONCAT() / || |
| Date addition | DATE_ADD() | INTERVAL |
| Current timestamp | NOW() | NOW() |
| Conditional expression | IF() / CASE | CASE |
| NULL handling | IFNULL() / COALESCE() | COALESCE() |
| Upsert | ON DUPLICATE KEY UPDATE | ON CONFLICT |
| String splitting | SUBSTRING_INDEX() | SPLIT_PART() |
| Returning modified rows | Limited alternatives | RETURNING |
| Full outer join | Not directly supported | Supported |
| JSON support | JSON | JSON / JSONB |

*Syntax and feature availability can vary by database version. I will practice database-specific implementations wherever necessary.*

## Progress Tracking

My progress will be documented through solved questions, SQL scripts, screenshots, and learning notes.

| Learning Area | Status |
|---|---|
| SQL Fundamentals | Completed |
| Filtering and Sorting | Completed |
| Aggregate Functions | Completed |
| SQL Joins | Completed |
| Subqueries | Completed |
| Conditional Logic | Completed |
| CTEs | Completed |
| Window Functions | Completed and Practicing |
| Set Operations | Completed |
| String and Date Functions | Partially Completed and In Progress |
| Database Design | In Progress |
| SQL and NoSQL | In Progress |
| ACID Properties | Completed |
| BASE Properties | Completed |
| CAP Theorem | Completed |
| DDL, DML, DCL, TCL, DQL(Select) | Completed |
| Transactions | In Progress |
| Indexing and Optimization | In Progress |
| Advanced SQL | In Progress |
| SQL Problem-Solving Patterns (Gaps & Islands, Running Totals, Sessonization, Top-N, MoM/YoY Growth, Deduplication, Pivot/Crosstab, Recursive/Hierarchial,Moving Averages and window frame clauses, funnel/retention cohort analysis) | In Progress |

*Status will be updated as concepts are learned and practiced.*

## Repository Organization

Learning materials will be organized by platform, topic, and difficulty wherever applicable.

```text
SQL-Progress-Tracking/
├── README.md
├── sql-practice.com/
├── datalemur/
├── stratascratch/
├── hackerrank/
├── leetcode/
├── sqlbolt/
├── sqlnest/
```

Each platform folder may contain:
- Easy, Medium, and Hard questions
- SQL query files (.sql)
- Screenshots of completed problems
- Problem statements and solutions
- Explanations and learning notes

The repository structure will evolve as more practice resources and concepts are added.

## Learning Objectives

- Develop strong SQL fundamentals and advanced querying skills.
- Become proficient in MySQL and PostgreSQL.
- Solve SQL problems across different difficulty levels.
- Master commonly used SQL interview patterns.
- Apply SQL to real-world business and analytical problems.
- Improve query readability, efficiency, and optimization.
- Understand relational database design and management.
- Maintain consistent proof of work and learning progress.
- Build practical SQL skills for Data Analyst and Business Analyst roles.

## Acknowledgements

I acknowledge the various open-source learning platforms, educational websites, documentation, and content creators that support my SQL learning journey.

All platform names, learning materials, and practice questions belong to their respective owners. This repository is an independent personal learning and practice portfolio and is not affiliated with these platforms.

---

**Repository Status:** Actively Learning & Practicing

**Primary Technologies:** MySQL | PostgreSQL

**Focus:** SQL Fundamentals | Advanced SQL | Problem-Solving | Data Analytics | Interview Preparation
