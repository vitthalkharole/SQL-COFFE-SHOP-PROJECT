# ☕ Monday Coffee Sales Analysis Using SQL

## 📌 Project Overview

This project analyzes the sales performance of **Monday Coffee**, a fictional coffee chain, using **MySQL**. The goal is to derive meaningful business insights by writing SQL queries that answer real-world business questions related to customers, products, cities, and sales.

The project demonstrates SQL concepts such as **Joins, Aggregate Functions, Common Table Expressions (CTEs), Window Functions, Date Functions, and Ranking**.

---

## 🛠️ Technologies Used

* MySQL
* SQL
* MySQL Workbench

---

## 📂 Database Schema

The database consists of four relational tables:

### 1. City

Stores information about cities where the company operates.

* City ID
* City Name
* Population
* Estimated Rent
* City Rank

### 2. Customers

Stores customer information.

* Customer ID
* Customer Name
* City ID (Foreign Key)

### 3. Products

Stores coffee product details.

* Product ID
* Product Name
* Price

### 4. Sales

Stores transaction details.

* Sale ID
* Sale Date
* Product ID (Foreign Key)
* Customer ID (Foreign Key)
* Total Sale Amount
* Customer Rating

---

## 📊 Business Questions Solved

### 1. Estimated Coffee Consumers

* Estimate the number of coffee consumers in each city, assuming **25% of the population drinks coffee**.

---

### 2. Revenue Analysis

* Calculate the total revenue generated during the **last quarter (Q4) of 2023**.

---

### 3. Product Performance

* Find the total number of orders for each coffee product.
* Identify the best-selling coffee products.

---

### 4. Average Customer Spending

* Calculate the average sales amount per customer in each city.

---

### 5. Customer vs Market Potential

* Compare the current number of unique customers with the estimated coffee-consuming population for every city.

---

### 6. Top Selling Products by City

* Identify the **Top 3 coffee products** in every city using SQL Window Functions.

---

## 📚 SQL Concepts Used

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* Aggregate Functions

  * SUM()
  * COUNT()
  * AVG()
  * ROUND()
* INNER JOIN
* LEFT JOIN
* Common Table Expressions (CTEs)
* Window Functions

  * DENSE_RANK()
* Date Functions

  * YEAR()
  * QUARTER()

---

## 📈 Key Business Insights

* Estimated coffee consumers by city.
* Quarterly revenue performance.
* Best-selling coffee products.
* Average customer spending across cities.
* Customer penetration compared to market size.
* Top-performing products in each city.

---

## 📁 Project Structure

```text
Monday-Coffee-Sales-Analysis/
│
├── coffee_sales_analysis.sql     # Complete SQL queries
├── README.md                     # Project documentation
└── dataset/                      # CSV files (optional)
```

---

## 🚀 How to Run

1. Create a MySQL database named **COFFEE**.
2. Execute the table creation script.
3. Import the CSV files in the following order:

   * city
   * products
   * customers
   * sales
4. Run the SQL queries in `coffee_sales_analysis.sql`.
5. Analyze the generated business insights.

---

## 🎯 Skills Demonstrated

* SQL Query Writing
* Relational Database Design
* Business Intelligence
* Data Analysis
* Data Aggregation
* Window Functions
* CTEs
* Data Modeling
* Analytical Thinking

---

## 💡 Future Improvements

* Create Power BI or Tableau dashboards.
* Develop monthly and yearly sales trend reports.
* Add stored procedures and SQL views.
* Optimize performance using indexes.
* Build customer segmentation and loyalty analysis.

---

## ⭐ Learning Outcomes

This project helped strengthen my understanding of:

* SQL Fundamentals
* Multi-table Joins
* Aggregate Functions
* Common Table Expressions (CTEs)
* Window Functions
* Date Functions
* Business Data Analysis
* Writing interview-oriented SQL queries

---

## 👨‍💻 Author

**Vitthal Kharole**

Computer Science Engineering Student

Interested in **SQL, Data Analytics, Data Engineering, Python, Power BI, and Business Intelligence**.

---

### ⭐ If you found this project useful, consider giving it a Star!
