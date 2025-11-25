📘 Library Management System – SQL Project

This project contains a complete SQL-based Library Management Database, including database creation, table design, constraints, and analytical queries.

🏛️ Project Overview

Designed and implemented a fully functional Library Management System using SQL.
The database includes information about publishers, books, authors, borrowers, library branches, book copies, and loan transactions.

This script includes:

DDL (schema creation)

DML (data insertion)

SQL queries for analysis and reporting

📄 Project File: SQL_FINAL_PROJECT.sql 

SQL_FINAL_PROJECT

🛠️ Technologies Used

MySQL / SQL Workbench

SQL DDL (CREATE, ALTER)

SQL DML (INSERT, UPDATE)

JOINS (INNER, LEFT)

Aggregations (COUNT, GROUP BY)

Constraints (PK, FK, NOT NULL, UNIQUE)

🗂️ Database Structure

The project includes the following tables:

tbl_publisher – Publisher details

tbl_book – Books and their publishers

tbl_book_authors – Book and author mapping

tbl_library_branch – Library branch information

tbl_book_copies – Available copies per branch

tbl_borrower – Borrower details

tbl_book_loans – Loan transactions

All tables include:

Primary Keys

Foreign Keys

Referential integrity

📊 Sample Queries Included

The script contains practical business queries, such as:

Books authored by Stephen King in specific branches

Borrowers with zero or more than 5 loans

Number of copies per branch

Books loaned from specific branches with due dates

Total loans per library branch

These queries demonstrate real-world data analysis scenarios.

📌 Highlights

Fully normalized database

Clean schema with relations and constraints

Dataset inserted for testing

Analytical queries included

Easy to run on any SQL editor

🚀 How to Use

Copy the SQL file into your SQL Workbench / MySQL editor.

Run the script step-by-step:

CREATE DATABASE

CREATE TABLES

INSERT DATA

Execute SELECT queries
