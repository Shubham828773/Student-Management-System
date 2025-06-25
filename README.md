Student Management System - Java Swing GUI
Overview
This is a simple Student Management System implemented in Java using the Swing framework. It provides a graphical user interface (GUI) where users can:

Enter student details (Name, Roll Number, Degree)

Enter marks for 4 subjects

Calculate total marks, percentage, and grade

View the result in a formatted text area

Features
User-friendly GUI for data entry and result display

Input validation for marks (ensures values between 0 and 100)

Automatic calculation of total, percentage, and grade

Scrollable result area for displaying output

Requirements
Java Development Kit (JDK) 8 or higher

How to Run
Compile the code:

Open a terminal/command prompt and navigate to the directory containing the .java file. Run:

bash
Copy
Edit
javac StudentManagementGUI.java
Run the application:

bash
Copy
Edit
java StudentManagementGUI
GUI Layout
The GUI consists of:

Text fields for:

Student Name

Roll Number

Degree

Marks for 4 subjects

A button: "Calculate Result"

A scrollable text area to display the result summary

Grading Criteria
Percentage Range	Grade
90 - 100	A+
75 - 89	A
60 - 74	B
50 - 59	C
40 - 49	D
Below 40	F

Notes
All mark inputs must be valid integers between 0 and 100.

If invalid input is detected, an error message is shown in the result area.

License
This project is provided for educational purposes and is free to use and modify.
