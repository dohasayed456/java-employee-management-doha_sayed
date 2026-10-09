# Employee Management System

**Full Name:** Doha Sayed Abdel Fattah Mohammed
**Student ID:** 2301894

## Description
A Java project that implements the given class diagram. It models an employee
management system with an abstract `Employee` class and three subclasses:
`CommissionEmployee`, `MonthlyEmployee`, and `HourlyEmployee`. Each one calculates
its salary differently. The `Department` class manages a list of employees
(add, remove, find, print, and calculate total payroll). `Gender` is an enum.

## Project Structure
```
src/
├── model/
│   ├── Employee.java
│   ├── CommissionEmployee.java
│   ├── MonthlyEmployee.java
│   ├── HourlyEmployee.java
│   ├── Department.java
│   └── Gender.java
└── test/
    └── MainTest.java   (demo with sample data)
```

## How to Run
Requirements: JDK 11 or higher.

From the project root folder:

```
javac -d out src/model/*.java src/test/MainTest.java
java -cp out test.MainTest
```

Or open the project in IntelliJ IDEA / Eclipse / VS Code and run `MainTest.java`.
