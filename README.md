# Student–Course–Enrollment Database

## 📌 Objective
Practice creating databases, tables, and relationships using *MySQL Workbench*.

## 🛠 Tools
- MySQL Workbench
- SQL (MySQL syntax)

## 📜 What I Did
1. Created a schema CollegeDB with the following tables:
   - Students
   - Instructors
   - Courses
   - Enrollments (junction table for many-to-many)

2. Defined *relationships*:
   - Students ↔ Enrollments ↔ Courses (Many-to-Many)
   - Instructors ↔ Courses (One-to-Many)

3. Generated an *ER Diagram* using MySQL Workbench (Reverse Engineer).

## 📂 Repository Structure
- sql/schema.sql → SQL script to create schema
- screenshots/ → ER diagram & Workbench screenshots
- README.md → Explanation of the task
