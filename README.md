This project implements a PostgreSQL database for managing student and course information. It imports data from CSV files and generates the following tables: students, courses, majors, and courses_majors. The database structure ensures data integrity and supports future extensions such as course enrollment tracking or student performance analysis.

Requirements:
- PostgreSQL 12.x or higher

Setup
1. Import the provided students.sql file into PostgreSQL: psql -U your_user -d your_database -f students.sql

2. Load the CSV files (students.csv, courses.csv) into their respective tables.
