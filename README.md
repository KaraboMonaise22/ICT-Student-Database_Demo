# ICT Student Results Database

SQL Server database for managing modules, students and test marks.

## What this database does
This project creates a small academic system where students are enrolled in modules and their test marks are recorded. It shows relational design with Primary Keys and Foreign Keys.

## Tables
1.  **MODULES** (MODULE_CODE PK, MODULE_NAME)
2.  **STUDENTS** (STUDENT_NUMBER PK, STUDENT_NAME, SURNAME, DOB)
3.  **TEST_RESULTS** (MODULE_CODE FK, STUDENT_NUMBER FK, TEST_NUMBER, TESTMARK)

## Relationship
- One student can have many test results
- One module can have many test results
- TEST_RESULTS is the linking table

## How to run
1. Open SQL Server Management Studio
2. Run `CREATE DATABASE ICT;`
3. Run the rest of the script

## Skills used
SQL Server, CREATE TABLE, PRIMARY KEY, FOREIGN KEY, SMALLDATETIME, VARCHAR
