# 📘 Task 1: Database Setup and Schema Design – SQL Developer Internship

## 🔍 Objective
The goal of this task is to demonstrate your understanding of database design by:
- Creating a well-structured relational database schema
- Writing clean and efficient SQL code
- Designing a clear and normalized ER diagram
- Applying key concepts like normalization, constraints, and relationships

---

## 🧰 Tools Used
- MySQL Workbench (for schema creation and ER diagram)
- dbdiagram.io (for online ER visualization)
- GitHub (for version control and submission)

---

## 🏢 Domain: Library Management System

This project models a **Library Management System**, which manages:
- Books and their authors
- Book categories
- Library members
- Loans (borrowing records)

---

## 🧱 Database Schema Overview

### 📄 Tables and Relationships

| Table         | Description                              |
|---------------|------------------------------------------|
| `Authors`     | Stores information about book authors    |
| `Categories`  | Stores different book genres/categories  |
| `Books`       | Stores book details, links to category   |
| `BookAuthors` | Join table for many-to-many relationship between books and authors |
| `Members`     | Library members who borrow books         |
| `Loans`       | Tracks which member borrowed which book  |

---

## 🗃️ Key Concepts Used

- **Primary Keys** to uniquely identify records
- **Foreign Keys** to define relationships between tables
- **Many-to-Many** relationships via join tables
- **AUTO_INCREMENT** for surrogate keys
- **Normalization** to avoid redundancy and improve structure

---

## 🧾 SQL Script

The full SQL schema is included in [`schema.sql`](schema.sql).  
To execute:

```sql
SOURCE schema.sql;
