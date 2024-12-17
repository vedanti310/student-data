
# Student Grade Management System

## Project Overview
This project implements a simple Python class that captures and manages student grades. The class includes methods for adding grades, calculating averages, and displaying the grades for individual students. Different test cases are provided to verify the functionality of the methods.

## Objectives
- To implement a class that manages students' grades.
- To implement various methods such as adding grades, calculating averages, and displaying student information.
- To write test cases for validating the functionality of each method.
- To practice DevOps principles by automating the test cases and setting up a testing framework.

## Features
- **Add Grade**: Allows adding grades for students.
- **Calculate Average**: Calculates the average grade of a student.
- **Display Grades**: Displays all grades for a student.

## Class Structure
The `StudentGrades` class has the following methods:
1. `add_grade(grade)` - Adds a grade to the student's grade list.
2. `get_average()` - Returns the average grade of the student.
3. `get_grades()` - Returns a list of all grades.
4. `display_grades()` - Displays the grades in a formatted manner.

## Example Usage

```python
# Create a student object
student = StudentGrades("John Doe")

# Add grades
student.add_grade(85)
student.add_grade(90)
student.add_grade(78)

# Get average grade
average = student.get_average()
print(f"Average Grade: {average}")

# Display grades
student.display_grades()
