# 1. SQL Introduction

## What is SQL?
SQL (Structured Query Language) is a standard language used to **communicate with relational databases**.
It allows users to:
- Retrieve data
- Insert new data
- Update existing data
- Delete unwanted data

In simple words:
> SQL is how we talk to databases.

---

## Why SQL Exists
Before SQL:
- Data was scattered
- Retrieval was slow
- Every system had its own rules

SQL standardized data communication so businesses could:
- Store structured data
- Query it efficiently
- Maintain data integrity

---

## Real-World Example
If a manager asks:
> "Show me all customers who purchased last month"

SQL translates that request into an executable query.

---

## Interview Perspective
**Common Question:**  
→ *What is SQL?*

**Answer:**  
SQL is a standard query language used to manage and manipulate relational databases.

---

## Key Takeaways
- SQL is declarative (you say *what*, not *how*)
- Used across almost every data-driven role
- Essential for analytics, backend, and reporting




# 2. Database Basics

## What is a Database?
A database is an organized collection of structured data stored electronically.

---

## Core Components

### 1. Table
Stores data in rows and columns.

### 2. Row (Record)
Represents a single data entry.

### 3. Column (Field)
Represents a data attribute.

---

## Example Table: employees

| emp_id | name | department | salary |
|--------|------|------------|--------|
| 101 | Ravi | IT | 60000 |

---

## Database vs Table

| Database | Table |
|--------|-------|
| Collection of tables | Collection of rows |
| Logical container | Actual data storage |

---

## Interview Question
**Q: Difference between database and table?**  
**A:** A database contains multiple tables, while a table contains actual data.

---

## Real-Life Analogy
Database → Folder  
Table → Excel sheet  
Row → Record  
Column → Field



# 3. Types of SQL Databases

## 1. Relational Databases (RDBMS)
- Structured schema
- Uses tables
- Supports joins

Examples:
- MySQL
- PostgreSQL
- SQL Server

Used in:
- Banking
- Analytics
- ERP systems

---

## 2. NoSQL Databases
- Schema-less
- Handles unstructured data
- High scalability

Examples:
- MongoDB
- Cassandra

---

## SQL vs NoSQL

| SQL | NoSQL |
|----|------|
| Structured | Semi-structured |
| Fixed schema | Dynamic schema |
| ACID compliant | High scalability |

---

## Interview Question
**Q: When would you use NoSQL over SQL?**

**A:** When handling large-scale unstructured or semi-structured data requiring flexibility and scalability.


# 4. SQL Architecture

## SQL Query Flow

User Query  
↓  
Parser  
↓  
Optimizer  
↓  
Execution Engine  
↓  
Result

---

## Step Explanation

### 1. Parser
- Checks syntax
- Validates objects

### 2. Optimizer
- Chooses best execution plan
- Uses indexes

### 3. Execution Engine
- Retrieves data
- Returns output

---

## Interview Question
**Q: What does the SQL optimizer do?**

**A:**  
It selects the most efficient way to execute a query by evaluating multiple execution plans.

---

## Why This Matters
Efficient queries = faster systems + happier users.
