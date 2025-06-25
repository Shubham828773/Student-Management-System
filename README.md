🎓 Student Management System (Java Swing)
A simple GUI-based Student Management System built using Java Swing. The application allows users to input student details and display the results in a formatted area. It is designed for educational purposes and to demonstrate basic GUI development with Java.

🧰 Features
User-friendly interface built with Java Swing

Input fields for:

Student Name

Roll Number

Degree

Marks (4 subjects)

Displays student details and marks

Can be extended with GPA calculation, validations, and data persistence

🖼️ GUI Preview
Insert a screenshot here once you have it

🚀 Getting Started
Prerequisites
JDK 8 or later

A Java IDE like IntelliJ IDEA, Eclipse, or simply use a text editor and command line

Running the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/student-management-system.git
Navigate to the project folder:

bash
Copy
Edit
cd student-management-system
Compile and run the program:

bash
Copy
Edit
javac StudentManagementGUI.java
java StudentManagementGUI
🧾 Code Overview
The project consists of two main classes:

StudentManagementGUI.java
This is the entry point of the application. It uses SwingUtilities.invokeLater() to ensure that the GUI is created on the Event Dispatch Thread (EDT).

StudentForm.java
This class handles all GUI components:

Uses JFrame, JLabel, JTextField, and JTextArea for layout

GridLayout organizes components in a structured 9x2 grid

Designed to be easily extendable for additional functionality (like buttons, validations, and storage)

🔧 Possible Enhancements
Add a Submit button to process and display results

Validate input fields

Compute and display average marks and grade

Store data using file I/O or a database

Add student search functionality
