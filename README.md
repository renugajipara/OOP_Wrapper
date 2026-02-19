🚀 Employee Management System (OOP-Based)



A menu-driven Python application demonstrating core Object-Oriented Programming (OOP) concepts including:

Inheritance

Encapsulation

Method Overriding

Polymorphism

Use of issubclass()

Python 3.10 match-case

This project simulates a simple Employee hierarchy system with different roles such as Employee, Manager, and Developer.



📌 Project Overview

The system allows users to:

✔ Create Employees

✔ Create Managers (Subclass of Employee)

✔ Create Developers (Subclass of Employee)

✔ Display object details dynamically

✔ Exit the system safely

It clearly demonstrates real-world class hierarchy modeling.



🏗 Class Structure
🔹 1️⃣ Employee (Base Class)

Attributes:

__em_id (Private)

name

age

__salary (Private)

Methods:

id_setdata() / id_getdata()

salary_setdata() / salary_getdata()

display()

__del__() (Destructor)

Encapsulation is achieved using private attributes.



🔹 2️⃣ Manager (Subclass of Employee)

Additional Attribute:

department

Concept Demonstrated:

Inheritance

Method Overriding (display())



🔹 3️⃣ Developer (Subclass of Employee)

Additional Attribute:

prog_lang

Concept Demonstrated:

Inheritance

Method Overriding (display())



🧠 OOP Concepts Demonstrated
Concept	Implementation

Encapsulation	Private attributes (__em_id, __salary)

Inheritance	Manager(Employee) & Developer(Employee)

Polymorphism	Overridden display() methods

Abstraction	Controlled access via getters/setters

Destructor	__del__() method

Type Checking	issubclass() usage



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



This project shows:

✔ Strong understanding of OOP principles

✔ Clean class hierarchy design

✔ Practical use of inheritance

✔ Encapsulation best practices

✔ Structured menu-driven logic



👩‍💻 Author

RENU
Aspiring Python Developer

Focused on mastering Object-Oriented Programming & clean architecture.
