# 📚 Book Store SQL Project

## Project Overview

This project demonstrates SQL concepts using a Book Store database in PostgreSQL. The database contains information about books, customers, and orders. Various SQL queries were used to analyze sales, inventory, customer behavior, and revenue.

## Database Schema

### Books Table

* Book_ID
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### Customers Table

* Customer_ID
* Name
* Email
* Phone
* City
* Country

### Orders Table

* Order_ID
* Customer_ID
* Book_ID
* Order_Date
* Quantity
* Total_Amount

## Technologies Used

* PostgreSQL
* SQL
* CSV Datasets
* pgAdmin

## SQL Concepts Covered

* CREATE TABLE
* PRIMARY KEY
* FOREIGN KEY
* INSERT & COPY Commands
* SELECT Statements
* WHERE Clause
* ORDER BY
* LIMIT
* DISTINCT
* Aggregate Functions (SUM, AVG, COUNT)
* GROUP BY
* HAVING
* INNER JOIN
* LEFT JOIN
* Data Analysis Queries

## Business Questions Solved

### Basic Analysis

1. Retrieve all books in the Fiction genre.
2. Find books published after 1950.
3. List customers from Canada.
4. Show orders placed in November 2023.
5. Calculate total stock available.
6. Find the most expensive book.
7. Find customers ordering more than one quantity.
8. Retrieve orders exceeding $20.
9. List all available genres.
10. Find the book with the lowest stock.
11. Calculate total revenue.

### Advanced Analysis

1. Total books sold by genre.
2. Average price of Fantasy books.
3. Customers with at least two orders.
4. Most frequently ordered book.
5. Top 3 most expensive Fantasy books.
6. Total quantity sold by each author.
7. Cities with customers spending more than $30.
8. Customer with the highest spending.
9. Remaining stock after fulfilling all orders.

## Key Learnings

* Designing relational databases.
* Working with multiple tables and relationships.
* Importing CSV files into PostgreSQL.
* Writing analytical SQL queries.
* Using joins and aggregations for business insights.
* Performing real-world data analysis with SQL.

## Project Files

* online_bookstore_sql_project.sql
* Books.csv
* Customers.csv
* Orders.csv

## Author
Sathwika chinnamula
BTECH(CSE-AIML)
