# Student-Record-Management-System-

Welcome to the Student Database Management System (SDMS)! This is a simple, console-based application built with Python for managing student records. It utilizes a JSON file to store and persist the data, acting as a lightweight, file-based database.

**Features**
This system provides basic CRUD (Create, Read, Update, Delete) functionalities essential for any management application:

Add Student (Create): Register a new student with their roll number, name, age, and course.

View Student (Read): Look up and display the details of a single student using their unique roll number.

Update Student (Update): Modify the name, age, or course details for an existing student.

Delete Student (Delete): Remove a student's record from the database.

View All Students (Read All): Display a list of all currently registered students.

**Prerequisites**
To run this application, you only need:

Python 3.x installed on your system.

**Getting Started**
1. Save the Code
Save the provided Python code into a file named student_manager.py (or any other name you prefer).

2. Run the Application
Open your terminal or command prompt, navigate to the directory where you saved the file, and run:

Bash

python student_manager.py
3. Interact with the Menu
The program will start and display a menu. Simply enter the number corresponding to the action you wish to perform and follow the on-screen prompts.

**Data Persistence**
All student records are stored in a file named students.json in the same directory as the script. This file is automatically created if it doesn't exist and updated every time you add, update, or delete a student.

The load_data() function handles reading the records from this file upon startup.

The save_data() function handles writing the records back to the file to save your changes.

Code Structure Overview
The code is organized into three main sections for clarity:

Helper Functions
load_data(): Checks for and loads data from students.json.

save_data(data): Writes the current data dictionary to students.json.

**Core Functionalities**
This section contains the main CRUD logic:

add_student(data)

view_student(data)

update_student(data)

delete_student(data)

view_all_students(data)

**Main Program Loop**
main(): Initializes the data, presents the menu, and directs the program flow based on user input until the user chooses to exit.

**Customization**
You can easily change the name of the data file by modifying the DATA_FILE constant at the top of the script.

The structure of the student data (name, age, course) is defined in add_student. To add more fields (e.g., email, GPA), you would need to update this function and the related view/update functions accordingly.

Would you like to see an example of how the students.json file would look after adding a student?
