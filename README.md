# MySQL Assignment

Name: Dinisha Jain  
Domain: AI / ML  

## Assignment Objective

The objective of this assignment is to understand the basics of MySQL by creating tables and performing SQL operations such as WHERE, AND, OR, NOT, ORDER BY, and LIKE.

## Tools Used

- MySQL Server / MySQL Workbench  
- GitHub  

## Database Creation

```sql
CREATE DATABASE college_db;
USE college_db;

Tables Created
Students Table
CREATE TABLE Students(
    student_id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    city VARCHAR(50)
);

Courses Table
CREATE TABLE Courses(
    course_id INT PRIMARY KEY,
    course_name VARCHAR(50),
    duration INT
);

Data Insertion
Insert into Students
INSERT INTO Students VALUES
(1, 'Amit', 21, 'Mumbai'),
(2, 'Neha', 22, 'Pune'),
(3, 'Rohit', 20, 'Delhi'),
(4, 'Nisha', 23, 'Mumbai');

Insert into Courses
INSERT INTO Courses VALUES
(101, 'Data Science', 6),
(102, 'Web Development', 4),
(103, 'AI and ML', 8);

SQL Operations
WHERE with AND
SELECT * FROM Students
WHERE age > 21 AND city = 'Mumbai';

WHERE with OR
SELECT * FROM Students
WHERE city = 'Mumbai' OR city = 'Pune';

WHERE with NOT
SELECT * FROM Students
WHERE NOT city = 'Delhi';

ORDER BY
SELECT * FROM Students
ORDER BY age ASC;

LIKE Operator
SELECT * FROM Students
WHERE name LIKE 'N%';

Output

All commands were executed using MySQL Workbench.
Screenshots of outputs are included in the assignment document.

# Conclusion

The MySQL database was successfully created, and conditional operations using WHERE, AND, OR, NOT, ORDER BY, and LIKE were performed successfully.
