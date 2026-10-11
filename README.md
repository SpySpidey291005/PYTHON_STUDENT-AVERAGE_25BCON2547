Student Utilities & Grading System

Project Description

A simple Python program that calculates the average of student marks, checks passing status against a fixed pass mark threshold, and determines academic grades.

Features

1. Calculates the average from a list of marks using a loop   
2. Evaluates if an individual mark meets or exceeds the passing threshold   
3. Assigns grade classifications (Distinction, First, Second, Fail) based on the average score   
4. Includes a unit test file to test the functions using Python's built-in unittest framework   

Requirements

1. Python 3.x   
2. Built-in unittest library (no external packages or requirements files needed)

Installation

1. Download or clone the repository containing student_utils.py and test_student_utils.py.   
2. Ensure both files are in the same directory.

How It Works
1. calculate_average(marks): Uses a for loop to sum the elements in the marks list and divides by the total count (len).
2. is_passing(mark): Compares an individual mark against the PASS_MARK constant (40) to return True or False.
3. get_grade(average): Uses conditional (if-elif-else) statements to return the correct grade category based on the average score ranges.

LicenseThis project is licensed under the MIT License.
