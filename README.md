# Business Expenses Tracking Database

## Project Overview

This project is a simple database system developed using MySQL to manage
business expenses in an organized way. The system stores expense
records, categorizes them, tracks payment methods and generates useful
reports using SQL queries.

The aim of this project is to replace manual expense recording with a
structured database so that data can be stored safely and retrieved
easily.

## Features

-   Store expense records
-   Categorize expenses (Food, Travel, Utilities, etc.)
-   Track payment methods (Cash, UPI, Card, etc.)
-   View complete expense reports
-   Generate summarized reports using SQL
-   Maintain data integrity using primary and foreign keys
-   Transaction support for safe data operations

## Database Tables

**User** -- Stores user details and role (Admin/User)\
**Category** -- Stores expense categories\
**Payment_Method** -- Stores payment types\
**Expense** -- Stores all expense records with references to other
tables

## Technologies Used

-   MySQL Server
-   MySQL Workbench
-   SQL (Structured Query Language)

## How to Run the Project

1.  Open MySQL Workbench
2.  Open the file `project_queries.sql`
3.  Execute the script
4.  Run SELECT queries to view reports

## Learning Outcomes

-   Learned database design and normalization
-   Implemented constraints and relationships
-   Performed joins and aggregate queries
-   Understood transaction handling in DBMS
-   Gained practical experience with MySQL
