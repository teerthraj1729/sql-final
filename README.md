Project Overview:-
The University Course Management System is a relational database project designed to demonstrate practical understanding of SQL concepts including database design, CRUD operations, joins, subqueries, aggregation, window functions, and conditional logic.
This project models a real-world university system involving students, courses, instructors, enrollments, and departments, and executes advanced SQL queries on the data.

Objective:-
The main objective of this project is to:
1)Design a normalized relational database
2)Implement all CRUD operations
3)Use JOINs, subqueries, GROUP BY, HAVING
4)Apply SQL functions (string, date, aggregate)
5)Use window functions and CASE expressions
6)Perform real-world query-based analysis

Database Schema:-
The system consists of the following tables:
Students
Courses
Instructors
Enrollments
Departments
Each table is connected using primary keys and foreign keys to maintain data integrity.

Tables Description:-
1)Students
Stores student-related information.
 1)StudentID->INT (PK)
 2)FirstName->VARCHAR
 3)LastName->VARCHAR
 4)Email->VARCHAR
 5)BirthDate->DATE
 6)EnrollmentDate->DATE
2)Courses
Stores course details.
 1)CourseID->INT (PK)
 2)CourseName->VARCHAR
 3)DepartmentID->INT (FK)
 4)Credits->INT
3)Instructors
Stores instructor details.
 1)InstructorID->INT (PK)
 2)FirstName->VARCHAR
 3)LastName->VARCHAR
 4)Email->VARCHAR
 5)DepartmentID->INT (FK)
 6)Salary->DECIMAL
4)Enrollments
Manages student-course relationships.
 EnrollmentID->INT (PK)
 StudentID->INT (FK)
 CourseID->INT (FK)
 EnrollmentDate->DATE
5)Departments
Stores academic departments.
 1)DepartmentID->INT (PK)
 2)DepartmentName->VARCHAR


SQL Operations Covered:-
CREATE, INSERT, UPDATE, DELETE (CRUD)
INNER JOIN & LEFT JOIN
Subqueries
GROUP BY & HAVING
Aggregate functions (COUNT, AVG, MAX)
String & Date functions
CASE expressions
Window functions (Running Total)


Queries Implemented:-
1)Perform CRUD operations on all tables
2)Retrieve students enrolled after 2022
3)Retrieve courses offered by Mathematics department
4)Count students enrolled in each course (with filter)
5)Students enrolled in both specific courses
6)Students enrolled in either specific course
7)Calculate average credits
8)Find maximum instructor salary by department
9)Count students per department
10)INNER JOIN – students with courses
11)LEFT JOIN – all students with courses
12)Subquery – students in high-enrollment courses
13)Extract year from enrollment date
14)Concatenate instructor names
15)Calculate running total of enrollments
16)Label students as Senior / Junior using CASE

Conclusion:-
The University Course Management System successfully demonstrates real-world database design and advanced SQL querying techniques. 
It provides a strong foundation for understanding relational databases and preparing for industry-level database applications
