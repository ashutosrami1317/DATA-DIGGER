# 📊 Data Digger - SQL Database Management Project

## 📖 Overview

**Data Digger** is a beginner-friendly SQL project that demonstrates the fundamentals of database management using MySQL. It includes the creation of a database and multiple tables along with CRUD (Create, Read, Update, Delete) operations and SQL queries.

The project manages customer information, orders, products, and order details for a simple retail system.

---

## 🚀 Features

- Create a MySQL database
- Create relational tables
- Insert sample records
- Retrieve data using SELECT queries
- Update existing records
- Delete records
- Sort and filter data
- Aggregate functions (SUM, MAX, MIN)
- Product sales analysis
- Order management

---

## 🗂️ Database Structure

### 1. Customers
Stores customer information.

| Column | Description |
|---------|-------------|
| CustomerID | Primary Key |
| Name | Customer Name |
| Email | Email Address |
| Address | Customer Address |

---

### 2. Orders

Stores customer orders.

| Column | Description |
|---------|-------------|
| OrderID | Primary Key |
| CustomerID | Customer Reference |
| OrderDate | Date of Order |
| TotalAmount | Total Order Value |

---

### 3. Products

Stores product details.

| Column | Description |
|---------|-------------|
| ProductID | Primary Key |
| ProductName | Product Name |
| Price | Product Price |
| Stock | Available Stock |

---

### 4. OrderDetails

Stores ordered products.

| Column | Description |
|---------|-------------|
| OrderDetailID | Primary Key |
| OrderID | Order Reference |
| ProductID | Product Reference |
| Quantity | Quantity Ordered |
| Sub_Total | Total Price |

---

## 🛠 SQL Operations Included

### Customers

- Create Customers Table
- Insert Customer Records
- Display All Customers
- Update Customer Address
- Delete Customer
- Search Customer by Name

### Orders

- Create Orders Table
- Insert Orders
- Display Orders
- Update Order Amount
- Delete Orders
- Retrieve Recent Orders

### Products

- Create Products Table
- Insert Products
- Sort Products by Price
- Update Product Price
- Delete Out-of-Stock Products
- Find Products Between Price Range
- Find Most Expensive & Cheapest Product

### Order Details

- Insert Order Details
- View Order Details
- Calculate Total Revenue
- Find Top Ordered Products
- Count Product Sales

---

## 📚 SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT
- WHERE
- UPDATE
- DELETE
- ORDER BY
- BETWEEN
- GROUP BY
- COUNT()
- SUM()
- MAX()
- MIN()
- LIMIT

---

## 💻 Technologies Used

- MySQL
- SQL
- MySQL Workbench (Recommended)

---

## ▶️ How to Run

1. Open MySQL Workbench.
2. Create a new SQL script.
3. Copy the SQL code into the editor.
4. Execute the script.
5. Run the SELECT queries to verify the output.

---

## 📂 Project Structure

```
Data-Digger/
│
├── DATA DIGGER.sql
└── README.md
```

---

## ⚠️ Notes

The uploaded SQL script contains a few spelling and syntax errors that should be corrected before execution, for example:

- `PRIMERY` → `PRIMARY`
- `VARCHER` → `VARCHAR`
- `Emaill` → `Email`
- `Addres` → `Address`
- `prodictID` → `productID`
- Missing foreign key constraints
- Duplicate `CREATE TABLE products` (the second one should be `CREATE TABLE orderdetails`)

---

## 🎯 Learning Outcomes

This project helps beginners understand:

- Database creation
- Table design
- CRUD operations
- Data filtering
- Sorting
- Aggregate functions
- Basic SQL reporting
- Relational database concepts

---

## 👨‍💻 Author

**Ravindra**

Beginner SQL Database Management Project for learning MySQL fundamentals.

---

⭐ If you found this project helpful, consider giving it a star!
