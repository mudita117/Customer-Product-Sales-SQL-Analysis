# 📊 SQL Business Analytics Project  
**Customer • Product • Sales Data Analysis using SQL**

---

## 📌 Project Summary
This project showcases **end-to-end business data analysis using SQL** on a retail dataset containing **Customers, Products, and Sales** data.

The objective of this project is to answer real-world business questions using SQL and demonstrate strong analytical thinking, data exploration, and advanced query writing skills.

The repository contains **30+ analytical SQL queries** ranging from basic exploration to advanced analytics using:

- Joins  
- Aggregations  
- CTEs  
- Window Functions  
- Time Intelligence  
- Customer Segmentation  

This project simulates how SQL is used by **Data Analysts and Business Analysts in real companies**.

---

## 🎯 Business Objective
Retail companies collect large volumes of transactional data.  
The challenge is converting raw data into **actionable business insights**.

This project answers questions such as:

- How much revenue is generated?
- Who are the most valuable customers?
- Which products perform best and worst?
- How do sales change over time?
- Which product categories drive the most revenue?
- How can customers be segmented based on behaviour?

---

## 🗂️ Database Schema
The project uses a **Star Schema** with one fact table and two dimension tables.

### 🔹 Tables Used

| Table Name | Description |
|------------|-------------|
| **dim_customers** | Customer demographics and location |
| **dim_products** | Product categories, cost and pricing |
| **fact_sales** | Sales transactions, quantity, revenue and order dates |

---

## 🛠️ Tools & Technologies
- MySQL Workbench
- Git & GitHub

---

## 🧠 SQL Skills Demonstrated

### 🔹 Basic SQL
- SELECT, WHERE, ORDER BY
- DISTINCT exploration
- Aggregations (SUM, COUNT, AVG)

### 🔹 Intermediate SQL
- GROUP BY analysis
- Multi-table JOINs
- Business KPI reporting
- Date & time functions

### 🔹 Advanced SQL
- Common Table Expressions (CTEs)
- Window Functions
- Ranking & Running Totals
- Customer Segmentation
- Year-over-Year Analysis

---

## 📊 Business Questions Solved

### 1️⃣ Business Overview Metrics
- Total Sales Revenue
- Total Orders
- Total Quantity Sold
- Average Selling Price
- Total Customers & Products

### 2️⃣ Customer Analytics
- Customers by country and gender
- Revenue generated per customer
- Top 10 high-value customers
- Customers with the fewest orders
- Customer segmentation into:
  - VIP Customers
  - Regular Customers
  - New Customers

### 3️⃣ Product Analytics
- Products by category
- Average cost per category
- Top 5 best-selling products
- Worst performing products
- Product cost segmentation

### 4️⃣ Sales & Revenue Analysis
- Revenue by product category
- Sales distribution across countries
- Monthly and yearly sales trends
- Running total sales over time

### 5️⃣ Time Intelligence Analysis
- First and last order date
- Order duration in months
- Youngest and oldest customer analysis
- Monthly performance tracking

### 6️⃣ Advanced Business Analytics
- Year-over-Year product performance
- Category contribution to total revenue
- Customer lifetime value segmentation



---

## 🚀 How to Run the Project
1. Clone this repository  
2. Open MySQL Workbench (or any SQL IDE)  
3. Create a database (example: `data_analytics`)  
4. Import the dataset tables  
5. Run the SQL queries file to reproduce the analysis

---

## 🎓 Skills Highlighted
✔ SQL for Data Analysis  
✔ Business Problem Solving  
✔ Analytical Thinking  
✔ Data Exploration  
✔ GitHub Project Documentation  

---

## 📸 Project Preview (Query Results)

Below are some sample previews of the SQL analysis performed on the dataset.

> 📌 Screenshots are taken from MySQL Workbench query outputs.

---

### 🔹 Business KPI Overview
Summary dashboard query showing:
- Total Sales  
- Total Orders  
- Total Quantity  
- Average Price  
- Total Customers & Products  

![Business KPI](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/KPI_results.png)

---

### 🔹 Percentage of Total Sales by Category
Analysis showing how each product category contributes to overall revenue.

![Sales by Category](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/%25_of_total_sales_by_category.png)

---

### 🔹 Running Total & Moving Sales Trend
Time-series SQL analysis showing cumulative sales growth over time.

![Running Total](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/running_total_%26_moving_avg.png)

---

### 🔹 Product Sales Performance Comparison
Compares product performance using current sales, average sales and previous year sales to identify growth and underperforming products.

![Product Sales Comparison](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/sales_comparison.png)

---

---

### 🔹 Customer Segmentation
Customers grouped into:
- VIP Customers  
- Regular Customers  
- New Customers  

![Customer Segments](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/total_customers_by_segment.png)

---

### 🔹 Customer Report
This report consolidates key customer metrics and behaviours. 

![Customer Report](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/Customer_report.png)

---

### 🔹 Product Report
This report consolidates key product metrics and behaviours.

![Product Report](https://github.com/mudita117/Customer-Product-Sales-SQL-Analysis/blob/main/Product_report.png)
