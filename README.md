
# Student Management System and Age Calculator

This repository contains two Python scripts implementing a Student Management System and an Age Calculator. Both scripts are developed using the PyQt6 library to create graphical user interfaces.

## Student Management System

### `main.py`

This script implements a Student Management System using PyQt6. It offers functionalities to add, edit, search, and delete student records in a SQLite database. The graphical user interface includes a main window with a table to display student data, a toolbar for easy access to features, and various dialog windows for interactions.

- `MainWindow`: The main application window displaying the student records in a table. Users can perform actions such as adding, editing, and deleting records.
- `DatabaseConnection`: Handles database connections and queries.
- `AboutDialog`: Displays information about the application.
- `EditDialog`: Allows editing student records.
- `DeleteDialog`: Enables deleting student records.
- `InsertDialog`: Supports adding new student records.
- `SearchDialog`: Facilitates searching for specific student records.

### `database.db`

The SQLite database file that stores student information.

### Usage

1. Run `main.py` to launch the Student Management System.
2. Use the menu, toolbar, and dialogs to manage student records.

## Age Calculator

### `example.py`

This script implements an Age Calculator using PyQt6. The graphical user interface allows users to input a name and date of birth, and it calculates the person's age based on the provided date.

- `AgeCalculator`: Creates a window with input fields and a button to calculate the age.

### Usage

1. Run `example.py` to launch the Age Calculator.
2. Input a name and date of birth and click "Calculate Age" to see the calculated age.

**Note:** These projects serve as educational examples and might not include advanced features or optimizations found in production software.

---
