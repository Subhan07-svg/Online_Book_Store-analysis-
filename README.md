# # 📚 Online Bookstore Analysis using SQL

## 📌 Project Overview

The Online Bookstore Analysis project focuses on analyzing an online bookstore's data using SQL. The project contains three datasets: Books, Customers, and Orders.

The purpose of this project is to extract meaningful information from the data, analyze sales performance, understand customer purchasing behavior, and manage book inventory using SQL queries.

This project helps demonstrate practical SQL skills through real-world business questions and data analysis.

## 🎯 Project Objective

The main objectives of this project are:

- To analyze book details, prices, genres, and available stock.
- To calculate total sales revenue and the number of books sold.
- To identify popular books, authors, and genres.
- To analyze customer orders and purchasing behavior.
- To identify customers who place multiple orders.
- To find high-value customers based on their spending.
- To calculate remaining book stock after sales.
- To practice SQL queries for solving business problems.

## 🗂️ Dataset Description

This project uses three datasets.

### 1. Books Dataset
Contains information about the books available in the bookstore.

Important columns:
- `Book_ID`
- `Title`
- `Author`
- `Genre`
- `Published_Year`
- `Price`
- `Stock`

### 2. Customers Dataset
Contains customer information.

Important columns:
- `Customer_ID`
- `Name`
- `Email`
- `Phone`
- `City`
- `Country`

### 3. Orders Dataset
Contains information about customer orders.

Important columns:
- `Order_ID`
- `Customer_ID`
- `Book_ID`
- `Order_Date`
- `Quantity`
- `Total_Amount`

## 🛠️ Tools and Technologies

- **PostgreSQL** – Database management and SQL query execution
- **SQL** – Data retrieval, filtering, aggregation, and analysis
- **pgAdmin** – Database management and query execution
- **CSV Files** – Dataset storage and import

## 🗄️ Database Structure

The project uses three relational tables:

- **Books:** Stores book information, prices, genres, and stock.
- **Customers:** Stores customer details and locations.
- **Orders:** Stores customer transactions and order details.

The tables are connected through `Book_ID` and `Customer_ID`, allowing data to be analyzed across multiple tables using SQL joins.

## 🔍 Project Workflow

1. Create the `OnlineBookstore` database.
2. Create the Books, Customers, and Orders tables.
3. Import the CSV datasets into the corresponding tables.
4. Explore and retrieve data using SELECT queries.
5. Filter records using WHERE conditions.
6. Sort and limit results using ORDER BY and LIMIT.
7. Calculate totals and averages using aggregate functions.
8. Join tables to analyze customer orders and book sales.
9. Group data to identify sales trends and customer behavior.
10. Use SQL queries to answer business-related questions.

## 📊 SQL Analysis and Business Questions

### Basic SQL Analysis

- Retrieve books belonging to the Fiction genre.
- Find books published after 1950.
- List customers from Canada.
- Find orders placed in November 2023.
- Calculate the total stock of available books.
- Identify the most expensive book.
- Find orders where the quantity is greater than one.
- Retrieve orders with a total amount greater than $20.
- Display all distinct book genres.
- Find the book with the lowest stock.
- Calculate total revenue from orders.

### Advanced SQL Analysis

- Calculate the total number of books sold in each genre.
- Find the average price of Fantasy books.
- Identify customers who have placed at least two orders.
- Find the most frequently ordered book.
- Identify the three most expensive Fantasy books.
- Calculate the total books sold by each author.
- Find cities associated with orders above $30.
- Identify the customer who spent the most money.
- Calculate the remaining stock after accounting for ordered quantities.

## 💻 SQL Concepts Used

The project demonstrates the following SQL concepts:

- `SELECT` – Retrieve data from tables.
- `WHERE` – Filter records based on conditions.
- `ORDER BY` – Sort query results.
- `LIMIT` – Restrict the number of returned rows.
- `DISTINCT` – Retrieve unique values.
- `SUM()` – Calculate totals.
- `AVG()` – Calculate averages.
- `COUNT()` – Count records.
- `GROUP BY` – Group records for analysis.
- `HAVING` – Filter grouped results.
- `INNER JOIN` and `LEFT JOIN` – Combine related tables.
- Primary Keys and Foreign Keys – Establish relationships between tables.
- `COALESCE()` – Handle NULL values in calculations.

## 📁 Project Files

The project repository contains:

- `Books.csv` – Book information dataset
- `Customers.csv` – Customer information dataset
- `Orders.csv` – Orders dataset
- `SQL Project Question.pdf` – Project question 

## ▶️ How to Run the Project

1. Install PostgreSQL on your computer.
2. Open pgAdmin and create the `OnlineBookstore` database.
3. Create the required tables using the provided SQL scripts.
4. Import the Books, Customers, and Orders CSV files into their respective tables.
5. Open the SQL solutions file in the query editor.
6. Execute the queries to perform the analysis.
7. Review the query results to understand bookstore sales, inventory, and customer behavior.

**Note:** If the SQL scripts contain file paths from another computer, update those paths according to your own system before executing them.

## 📈 Expected Learning Outcomes

Through this project, I learned how SQL can be used to:

- Work with relational databases.
- Retrieve and filter data efficiently.
- Perform calculations using aggregate functions.
- Combine data from multiple tables.
- Analyze sales and customer behavior.
- Solve practical business problems using SQL.

## 📝 Conclusion

The Online Bookstore Analysis project demonstrates the practical application of SQL in business data analysis. By working with book, customer, and order datasets, the project explores inventory management, sales revenue, popular books, author performance, and customer purchasing patterns.

This project provides hands-on experience with SQL queries, relational database concepts, and data-driven problem-solving.

---

**Project Category:** Data Analysis  
**Domain:** Online Bookstore / Retail  
**Technology:** PostgreSQL and SQL



