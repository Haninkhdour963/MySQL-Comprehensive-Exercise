# MySQL-Comprehensive-Exercise
📘 University Course Management System – SQL Schema & Queries
This project implements a comprehensive University Course Management System using MySQL. It provides a structured relational database design along with sample data insertion, queries, stored procedures, functions, transactions, indexing, and performance analysis using EXPLAIN.

🧱 Schema Overview
The system manages data for:

👨‍🎓 Students

📚 Courses

👩‍🏫 Instructors

📖 Enrollments

🗂️ Course Assignments

🔗 Relationships
Students enroll in multiple courses.

Courses are assigned to instructors per semester.

Enrollments track grades.

Stored procedures control enrollment capacity.

📂 Tables
Students
Stores student information including personal details and academic major.

Courses
Holds course data such as name, code, credit hours, and department.

Instructors
Details about instructors and the departments they belong to.

Enrollments
Tracks which students are enrolled in which courses and their grades.

CourseAssignments
Maps instructors to the courses they teach, including semester and year.

📥 Sample Data
Sample records are inserted for:

10 students across multiple majors

5 courses from different departments

5 instructors with various hire dates

Student enrollments with grades

Instructor course assignments

🔍 Queries Included
A wide variety of SQL queries are provided to demonstrate:

Retrieving students enrolled in specific courses

Calculating course popularity and grade averages

Joining across multiple tables

Finding top-performing students

Aggregating department-level statistics

Listing courses without enrollments

Using stored procedures to enroll students with capacity checks

Using user-defined functions to calculate student age

Creating indexes for performance optimization

UNION queries for merged views of roles

EXPLAIN plans for performance analysis

⚙️ Stored Procedures & Functions
EnrollStudent: Safely enrolls a student into a course with a capacity check.

CalculateAge: Computes current age from date of birth.

📊 Performance
Indexing strategy (idx_course_code)

EXPLAIN statements used for analyzing join performance and query optimization

✅ Use Cases
This schema can be used in:

Academic information systems

Software engineering database assignments

Backend systems for course enrollment apps

Teaching relational database fundamentals

📌 Technologies Used
MySQL

SQL standard syntax

Stored procedures & functions

Transactions

Joins, Aggregates, Grouping

Data normalization

📝 License
This project is open-source and can be used for educational or personal development purposes.

