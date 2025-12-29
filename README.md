# Resturant and Consumer Data using SQL

## 📌 Project Overview
This project analyzes restaurant ratings using a relational database.
It focuses on understanding consumer behavior, preferences, and restaurant
performance through **SQL queries**.

The project demonstrates database design, relationships, filtering,
aggregations, joins, subqueries, CTEs, window functions, views,
and stored procedures.

---

## 🛠️ Technologies Used
- SQL
- MySQL (or any compatible RDBMS)

---

## 📂 Project Structure

SQL-Project/
│── Project SQL/
│ │── SQLCode.sql
│ │── SQLPPT.pptx
│── README.md


---

## 📊 Database Schema

**Database Name:** `RestaurantDB`

### Tables Used
- **consumers** – demographic and lifestyle information of consumers  
- **consumer_preferences** – preferred cuisines of consumers  
- **restaurants** – restaurant details and attributes  
- **restaurant_cuisines** – cuisines served by restaurants  
- **ratings** – ratings given by consumers to restaurants  

Primary and foreign key constraints are used to maintain referential integrity.

---

## 📥 Dataset Information
Dataset files are **not included** in this repository.

Data is assumed to be:
- Loaded locally into the database, or
- Inserted using `INSERT INTO` statements

This project emphasizes **SQL querying and analysis**, not dataset distribution.

---

## 🧩 SQL Concepts Covered

### 🔹 Basic SQL
- CREATE DATABASE & TABLE
- PRIMARY KEY & FOREIGN KEY
- INSERT INTO
- SELECT
- WHERE conditions
- GROUP BY & HAVING

### 🔹 Joins & Subqueries
- INNER JOIN
- Nested subqueries
- Filtering 

### 🔹 Advanced SQL
- Common Table Expressions (CTEs)
- Window Functions 
- Derived tables
- Views
- Stored Procedures

---

## 📈 Key Analysis Performed
- Consumers by city, occupation, budget, and lifestyle
- Restaurant ratings and performance comparison
- Cuisine-based restaurant analysis
- Student and age-based consumer behavior
- Identification of highly rated restaurants
- Consumer segmentation based on budget
- Ranking restaurants and consumers using window functions

---

## ▶️ How to Run the Project
1. Open MySQL.
2. Create a database:
   ```sql
   CREATE DATABASE RestaurantDB;
   USE RestaurantDB;
3. Execute the SQL file: SQLCode.sql
4. Run individual queries to view results.

---

## 🎯 Purpose of the Project
- To design and implement a relational database using SQL
- To apply advanced SQL concepts to solve real-world data analysis problems
- To analyze consumer behavior and restaurant performance
- To strengthen SQL skills for interviews, assessments, and practical use
