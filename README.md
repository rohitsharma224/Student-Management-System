# Student Management System

## Overview
This Java-based Student Management System is a console application that allows users to manage student records and their examination details. The system provides functionality to add new students, record examination marks for subjects, view student details, and view examination results with grades.

## Features

### Student Management
- Add new students with details:
  - Name
  - Roll Number
  - Date of Birth
  - Email
  - Student ID
  - Course
- View student details

### Examination Management
- Add examination details for 5 subjects per student
- Automatic grade calculation (A+, A, B+, B, C, D, F)
- Percentage calculation for each subject
- Overall performance calculation
- View comprehensive examination results

## Class Structure

1. **Student Class**
   - Stores and manages student personal information
   - Provides methods to display student details

2. **Subject Class**
   - Represents an academic subject
   - Stores marks and calculates grades/percentages

3. **Examination Class**
   - Manages multiple subjects for a student
   - Calculates overall performance metrics
   - Displays comprehensive results

4. **StudentManagementSystem Class**
   - Main application class with menu-driven interface
   - Handles user input/output
   - Manages student and examination data

## How to Use

1. **Compile and Run**
   - Compile: `javac StudentManagementSystem.java`
   - Run: `java StudentManagementSystem`

2. **Menu Options**
   - **1. Add New Student**: Enter student details
   - **2. Add Examination Details**: Add marks for 5 subjects for a student
   - **3. View Student Details**: View information for a specific student
   - **4. View Examination Results**: View exam results with grades
   - **5. Exit**: Quit the application

## Requirements
- Java JDK 8 or later
- Basic Java runtime environment

## Notes
- The system uses in-memory storage (no database)
- All data is lost when the program exits
- Input validation is implemented for marks (0-100 range)
