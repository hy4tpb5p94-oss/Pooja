# Student Record Management System (Menu-Driven)

## Overview
This is a menu-driven Python program to manage student records. It allows the user to add student details, view all records, search a student by ID, delete records, and store data permanently using file handling.

## Problem Addressed
Manual student record maintenance can lead to missing data, mistakes, and difficulty in searching. This program provides a simple digital way to store and manage student records.

## Main Features
- Add Student Record
- View Student Records
- Search Student by Student ID
- Delete Student Record
- Menu-driven console interface
- Input validation with try/except
- Save and load student data using file handling

## Data Storage Design
The program uses:
- **List** to store multiple student records
- **Dictionary** for each student record (one dictionary = one student)

## Python Concepts Used
### Control Flow
- while loop (menu repetition)
- if/elif/else (menu selection and validations)

### Functions
- add_student()
- view_students()
- search_student()
- delete_student()
- save_to_file()
- load_from_file()

### Methods Used
**List methods:** append(), pop(), len()  
**Dictionary methods:** get(), keys(), values()  
**String methods:** strip(), title()

### Exception Handling
try/except is used to handle invalid inputs (example: entering text instead of number for ID/marks).

## File Handling
Student data is saved and loaded using `open()` / `with open()` into a data file stored in the same folder.

## How to Run
1. Keep these files in the same folder:
   - Student Record Manager-Final Version.ipynb
   - student_data.txt (or student_data.csv if you changed to CSV)
2. Open the notebook
3. Run the program cell
4. Use the menu options shown in output

## Input Guidelines
- Student ID must be numeric
- Semester must be numeric
- Marks must be numeric
- Names/Course should be text

## Author Details
NAME: Pooja Suresh Hegde  
USN: 1BG24BA087  
COURSE: Python Programming  
PROJECT: Student Record Management System  
DOMAIN: Education / Academic Records  
