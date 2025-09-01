Student Management System

Overview
The Student Management System is a console-based C++ program that allows the user to manage student data. It provides functionalities to insert, search, display, delete, and update student records. This system stores basic student details such as roll number, name, section, and department. The program is implemented using Object-Oriented Programming (OOP) principles in C++.

Features
Insert Student Record: Allows the user to add a new student's record with details like roll number, name, section, and department.
Search Student Record: Lets the user search for a student's record using their roll number.
Display All Records: Displays all the student records stored in the system.
Delete Student Record: Deletes a student's record based on their roll number.
Update Student Record: Allows the user to update a student's section and department.
Exit: Terminates the program.

Requirements
A C++ compiler (e.g., GCC or Visual Studio) to compile and run the program.
Basic understanding of C++ programming  and Object-Oriented Programming (OOP) concepts.

How to Run
Clone or download the repository to your local machine.
Open the terminal (or IDE) and navigate to the folder containing the source code file.
Compile the code using a C++ compiler:

```bash
g++ -o StudentManagementSystem student_management_system.cpp
```
Run the program:

```bash
./StudentManagementSystem
```
The user will be prompted with the main menu to choose an option (Insert, Search, Display, Delete, Update, or Exit).

Code Structure
The project contains the following key components:

STUDENT Class:
Attributes: STU_ROLL, STU_NAME, STU_SEC, STU_DEPT.
Methods:
Insert: Adds a new student record.
Search: Searches for a student record based on roll number.
Display: Displays a student's details.
Del: Deletes a student record based on roll number.
Update: Updates a student's section and department.
Main Program:
Displays the menu and handles user input.
Executes the respective methods based on the user's choice.

Usage
Main Menu Options:
Insert: Adds a new student's record.
Search: Search for a student by roll number.
Display: Displays all student records.
Delete: Deletes a student's record by roll number.
Update: Updates the student's section or department.
Exit: Exit the system.
Example:

```bash
Enter Your Choice:
1   # For inserting a new student
Enter Roll: 101
Enter Name: John
Enter Section: A
Enter Department: Computer Science

Enter Your Choice:
3   # To display all records
ROLL  NAME  SEC  DEPT
=======================
101   John  A    Computer Science
```

Contributing
If you wish to contribute to this project, feel free to fork the repository and submit a pull request with your improvements or fixes. All contributions are welcome!

License
This project is open-source and available under the MIT License.

Contact
For any questions or feedback, feel free to reach out via the GitHub issues page.
