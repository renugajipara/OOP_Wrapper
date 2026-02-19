🚀 Employee Management System (OOP-Based)

A menu-driven Python console application built to demonstrate core Object-Oriented Programming (OOP) principles using real-world employee role modeling.

This project implements a structured class hierarchy consisting of:

👤 Employee (Base Class)

🧑‍💼 Manager (Subclass)

👩‍💻 Developer (Subclass)

Built using Python 3.10+ with modern match-case control flow.

📌 Project Overview

This application allows users to:

✔ Create Employees

✔ Create Managers (inherits from Employee)

✔ Create Developers (inherits from Employee)

✔ Display object details dynamically

✔ Exit the system safely

The system demonstrates how inheritance and polymorphism work in practical object modeling.

🏗 Class Architecture

🔹 1️⃣ Employee (Base Class)

Attributes

__em_id (Private)

name

age

__salary (Private)

Methods

id_setdata() / id_getdata()

salary_setdata() / salary_getdata()

display()

__del__() (Destructor)

🔒 Encapsulation is achieved through private attributes using double underscore (__).

🔹 2️⃣ Manager (Subclass of Employee)

Additional Attribute

department

Key Concepts Demonstrated

Inheritance

Method Overriding (display())

🔹 3️⃣ Developer (Subclass of Employee)

Additional Attribute

prog_lang

Key Concepts Demonstrated

Inheritance

Method Overriding (display())

🧠 OOP Concepts Implemented
Concept	Implementation in Project

Encapsulation	Private attributes (__em_id, __salary)

Inheritance	Manager(Employee) & Developer(Employee)

Polymorphism	Overridden display() 
methods
Abstraction	Controlled access via getters/setters
Destructor	__del__() 
method
Type Checking	issubclass()

📊 Class Hierarchy Diagram

classDiagram

class Employee {
  - __em_id
  - name
  - age
  - __salary
  + id_setdata()
  + id_getdata()
  + salary_setdata()
  + salary_getdata()
  + display()
}

class Manager {
  - department
  + display()
}

class Developer {
  - prog_lang
  + display()
}

Employee <|-- Manager
Employee <|-- Developer

📋 Menu Options
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

🛠 Technologies Used

Python 3.10+

VS Code

Console-Based Interface

💡 Learning Outcomes

This project strengthens understanding of:

Class design and structure

Inheritance relationships

Method overriding and polymorphism

Encapsulation best practices

Structured menu-driven applications

Real-world OOP modeling

🚀 Possible Enhancements

Add input validation (try-except)

Store multiple employees using lists/dictionaries

Add search and update functionality

Implement file/database persistence

Convert to GUI version (Tkinter / PyQt)

Add unit testing

👩‍💻 Author

RENU
Aspiring Python Developer
Focused on mastering Object-Oriented Programming and clean system architecture.

⭐ If you found this project useful, consider giving it a star on GitHub!
