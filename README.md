DBMS & SQL Practice

📌 Topics Covered

- Normalization
- Functional Dependency
- SQL Queries

💻 Sample Queries

Create Table

CREATE TABLE students (
id INT,
name VARCHAR(50),
age INT
);

Select Query

SELECT * FROM students;

Insert Query

INSERT INTO students VALUES (1, 'Akshat', 22);

🧠 Concepts Learned

- Data organization
- Query writing
- Database design basics
- 📌 Practice Examples

Update Query

UPDATE students SET age = 23 WHERE id = 1;

Delete Query

DELETE FROM students WHERE id = 1;

Conditional Query

SELECT * FROM students WHERE age > 20;
