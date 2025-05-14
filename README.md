# School Management System

This project aims to manage and track school data, including personal information about teachers and students, as well as grades and courses. The system is built using C# for the console application and SQL for managing the database with Entity Framework (EF) in Visual Studio.

## Features

### 1. **Menu for Data Display (Console Application)**
   - A simple console-based menu where users can choose between different options to view data requested by the school. The options include displaying information about staff, students, courses, and more.

### 2. **Staff Overview (SQL in SSMS)**
   - Display a list of all staff members with their names, positions, and the number of years they've worked at the school.
   - An administrator can also add new staff members to the system.

### 3. **Student and Grades Management (SQL in SSMS)**
   - Store and display information about students, including which class they belong to.
   - Store grades for each student in the courses they've taken, along with the name of the teacher who assigned the grade.
   - Each grade should also include a date to indicate when it was given.

### 4. **Teacher Count by Department (EF in VS)**
   - Retrieve and display the number of teachers working in different departments of the school.

### 5. **Show Information about All Students (EF in VS)**
   - Display a list of all students, along with their relevant details (e.g., name, grades, and courses).

### 6. **Active Courses List (EF in VS)**
   - Show a list of all active courses available in the system.

### 7. **Salary Payments by Department (SQL in SSMS)**
   - Retrieve and display the total salary payment each department makes every month.

### 8. **Average Salary by Department (SQL in SSMS)**
   - Show the average salary for each department.

### 9. **Stored Procedure for Student Information (SQL in SSMS)**
   - Create a stored procedure that takes a student ID and returns essential information about that student.

### 10. **Grade Assignment with Transactions (SQL in SSMS)**
   - Use transactions to ensure that grades can be safely assigned to students. If something goes wrong during the process, the transaction should be rolled back.

