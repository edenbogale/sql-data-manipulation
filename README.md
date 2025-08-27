# Data Manipulation and Transactions Assignment

This assignment demonstrates core SQL operations:
- Creating tables
- Inserting records
- Updating existing data

These are essential skills for managing relational databases.

## 📂 Files
- `answers.sql` – Contains all SQL queries for the assignment
- `README.md` – This file

## 📝 Assignment Questions & Answers

### Question 1: Create the `student` table
```sql
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);

id is the primary key (ensures uniqueness and indexing)
fullName uses VARCHAR(100) to limit name length
age stores integer values
Question 2: Insert 3 student records
sql
INSERT INTO student (id, fullName, age)
VALUES 
    (1, 'Alice Johnson', 19),
    (2, 'Ben Carter', 18),
    (3, 'Clara Diaz', 20);
Used a single INSERT with multiple rows for efficiency
All required fields are populated
Question 3: Update age of student with ID 2
sql
UPDATE student
SET age = 20
WHERE id = 2;
The WHERE clause ensures only one record is updated
Prevents accidental changes to other students
🛠️ How to Run
Open your SQL environment (e.g., MySQL Workbench, phpMyAdmin, or command line).
Run the queries in answers.sql in order.
Verify results using:
sql
SELECT * FROM student;
🧑‍🏫 Submitted By
Eden Bogale
Date: 2025

