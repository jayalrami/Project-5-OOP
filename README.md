🧑‍💼 Python OOP Project: Employee Management System
📌 Overview

The Employee Management System is a menu-driven Python program that demonstrates Object-Oriented Programming (OOP) concepts such as:

Inheritance

Encapsulation

Method overriding

Class relationships

The system allows users to create and manage Person, Employee, and Manager objects and display their details interactively.

🎯 Features

Create a Person with name and age

Create an Employee with ID and salary

Create a Manager with department information

Display stored details using a menu-based system

Demonstrates inheritance and method overriding

🏗️ Class Structure
1️⃣ Person

Attributes

name

age

Methods

_display() – Displays name and age

2️⃣ Employee (Inherits from Person)

Attributes

empid

salary

Methods

get_employee_id()

set_employee_id(empid)

display() – Displays person details plus employee information

3️⃣ Manager (Inherits from Employee)

Attributes

department

Methods

display() – Displays employee details plus department

4️⃣ Developer (Partially Implemented)

Intended to store programming language information

Currently contains constructor and naming issues

Needs fixes before use

🖥️ Program Flow

The program runs in a loop and provides the following menu:

1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit


Users can create objects and later view their details through a sub-menu.

▶️ How to Run

Make sure Python 3 is installed

Save the file as employee_management.py

Run the program:
