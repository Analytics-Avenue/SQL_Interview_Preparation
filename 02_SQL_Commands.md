# 📂 01_DDL — Data Definition Language

---

## What is DDL?

DDL commands are used to **define and manage database structures** such as tables, schemas, and columns.

Think of DDL as **building the house**, not living in it.

---

## Common DDL Commands

* `CREATE`
* `ALTER`
* `DROP`
* `TRUNCATE`

---

## CREATE

### Purpose

Creates new database objects such as tables, views, or schemas.

---

### Syntax

```sql
CREATE TABLE employees (
    emp_id INT PRIMARY KEY,
    name VARCHAR(50),
    department VARCHAR(30),
    salary INT
);

