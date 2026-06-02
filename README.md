
# 📊 Student Enrollment Database Project – SQL Functions & Joins

## 📌 Project Overview
This project demonstrates how to design and query a **Student Enrollment Database** using SQL.  
It covers:
- Database creation (DDL)
- Data insertion (DML)
- Joins (INNER, LEFT, RIGHT)
- String, numeric, and date functions
- Practical queries for reporting and analysis

---

## 🗂️ Database Schema
- **Students**: Stores student details (ID, Name, Age, City)
- **Courses**: Stores course details (ID, Name, Duration)
- **Enrollments**: Links students to courses with enrollment dates

---

## 🛠️ SQL Features Demonstrated
- **Joins**: INNER JOIN, LEFT JOIN, RIGHT JOIN
- **String Functions**: `CONCAT`, `LENGTH`, `REPLACE`, `SUBSTRING`, `UPPER`, `LOWER`
- **Numeric Functions**: `ROUND`, `ABS`, `MOD`
- **Date Functions**: `NOW()`, `DATEDIFF()`, `DATE_ADD()`

---

## 📸 Results & Screenshots

### 1. Students with their Enrollments (INNER JOIN)
<img width="700" height="467" alt="inner join" src="https://github.com/user-attachments/assets/208bbb41-9f9a-4da4-92b2-98897ea90b1f" />


### 2. Students with Courses (LEFT JOIN)
<img width="678" height="537" alt="left join" src="https://github.com/user-attachments/assets/f6683a4b-963d-454e-8d13-4a5c5e5d0920" />

### 3. Students with Courses (RIGHT JOIN)
<img width="616" height="501" alt="right join" src="https://github.com/user-attachments/assets/0b4552ba-28c7-47c9-ad4d-329c8bf25e54" />


### 4. String Functions Example
- CONCAT → `Aarav from Chennai`
 - <img width="675" height="292" alt="concat" src="https://github.com/user-attachments/assets/f1de65d8-d89a-4e31-ac46-6dbaeade0080" />

- LENGTH → Character count of names
-<img width="766" height="371" alt="charcter count" src="https://github.com/user-attachments/assets/1bcdca73-4b43-454c-a413-df86b99ee2d5" />
 


### 5. Numeric Functions Example
- ROUND(123.4567, 2) → `123.46`
- ABS(-15) → `15`
- MOD(25, 4) → `1`
![Numeric Functions Screenshot](screenshots/numeric_functions.png)

### 6. Date Functions Example
- Current Date/Time → `NOW()`
- Days Between → `DATEDIFF('2025-06-01','2025-05-10') = 22`
- Add 10 Days → `DATE_ADD(EnrollmentDate, INTERVAL 10 DAY)`
![Date Functions Screenshot](screenshots/date_functions.png)

---

## 🚀 How to Run
1. Copy the SQL script into your MySQL/MariaDB environment.
2. Execute step by step:
   - Create database and tables
   - Insert sample data
   - Run queries
3. Capture results and save screenshots in a `screenshots/` folder.

---

## 🎯 Learning Outcomes
- Understanding relational database design
- Practicing joins for combining data
- Applying SQL functions for reporting
- Building a portfolio‑ready SQL project

---

## 📧 Contact
Created by **Saranya**  
📍 India  
💼 Data Analyst | SQL | Power BI | Python  
