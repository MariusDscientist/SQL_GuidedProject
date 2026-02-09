# Guided SQL Project – PostgreSQL Fundamentals & Analysis

This project is a guided learning initiative focused on using PostgreSQL for database management, including data loading and analysis through SQL functions.

The main objective was to understand the complete process, from installing a database engine to executing queries and functions for data analysis.

---

## What was learned in this project

During the development of this project, the following points were addressed:

- Installation and configuration of PostgreSQL in a local environment.
- Creation and management of users, passwords, and databases.
- Use of pgAdmin as a graphical interface for PostgreSQL administration.
- Connection to a local database from pgAdmin.
- Data insertion methods, both with the query tool (`INSERT INTO`) and by importing CSV files.
- Design and execution of SQL functions (PL/pgSQL) for data analysis.
- Execution of queries focused on analysis and data exploration.

---

## Technologies used

- PostgreSQL
- pgAdmin
- SQL / PL/pgSQL
- Git & GitHub

---

## Project structure

```text
SQL_GuidedProject/
├── data/
|   ├── Customers.csv
|   ├── Sales.csv
│   └── project-db.txt
├── sql/
│   └──SQL-Window-Functions-for_Analytics.sql
├── README.md
└── .gitignore 
```

---

## Workflow

The development process followed these steps:

1. Installation of PostgreSQL in a local environment.
2. Creation of a user and a database.
3. Configuration of pgAdmin and establishing connection with the local server.
4. Creation of tables using SQL commands.
5. Data loading through manual insertions from the query tool and by importing CSV files.
6. Development of SQL functions for analysis.
7. Execution of analytical queries.

---

## Examples of analysis performed

Some examples of the analyzes carried out include:

*   Use of functions for aggregate calculations.
*   Data analysis based on custom functions.
*   Queries for data exploration and validation.

---
## Errors and solutions

During CSV data loading, permission errors appeared.
This occurred because PostgreSQL reads files as a server process, not as the system user.

To solve it:

A dedicated import directory was created, accessible only by the postgres user.

CSV files were loaded using the COPY command from the Query Tool.

CSV columns were mapped in order to a normalized SQL schema.

This point was especially valuable for understanding the difference between client (pgAdmin) and server (PostgreSQL).
---

## Additional notes

This project has an educational purpose, being developed as part of a guided learning process in relational databases and data analysis with SQL.

---

## Author

**Jhon Mario Cano Torres**
Physical Engineer | Junior Data Scientist