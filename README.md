# Banking-Management-System
A simple Desktop Banking Management System developed using Core Java and Java Swing.
This project is designed for learning Java basics, OOP concepts, and exception handling.

## Project Overview

The Banking Management System allows users to manage basic banking operations such as:

Login to the system
Add new bank accounts
Deposit money
Withdraw money
View all account details

This is a beginner-level project, suitable for students learning Core Java.

## Technologies Used
Language: Java
GUI: Java Swing
Concepts:
Object Oriented Programming (OOP)
Inheritance
Polymorphism
Encapsulation
Exception Handling
Serialization

IDE: IntelliJ IDEA / Eclipse / VS Code

 ##Features
Login screen for authentication
Add different account types:
Savings Account
Current Account
Student Account
Deposit money into account
Withdraw money with validation
Display all account details in GUI
Custom exception handling for errors

## Project Workflow
User launches the application
Login screen appears
After successful login, main dashboard opens
User selects an operation:
Add Account
Deposit
Withdraw
Display Account List
System processes request and shows result
User exits the application

📂 Project Structure
Banking-System/
│
├── Bank/
│   ├── Bank.java
│   ├── BankAccount.java
│   ├── SavingsAccount.java
│   ├── CurrentAccount.java
│   └── StudentAccount.java
│
├── Exceptions/
│   ├── AccNotFound.java
│   ├── InvalidAmount.java
│   ├── MaxBalance.java
│   └── MaxWithdraw.java
│
├── GUI/
│   ├── Login.java
│   ├── MainMenu.java
│   └── OtherScreens.java
│
└── README.md

## Custom Exceptions Used

AccNotFound – When account number does not exist
InvalidAmount – When entered amount is invalid
MaxBalance – When balance is insufficient
MaxWithdraw – When withdrawal limit exceeds

## Learning Outcomes
Understanding of Core Java fundamentals
Hands-on practice with OOP concepts
GUI development using Java Swing
Error handling using custom exceptions
Real-world problem solving

## Future Improvements
Integrate MySQL database
Add password encryption
Add transaction history
Convert to web application using Spring Boot

## Author
Riya Makwana
MCA (AI) Student
Java Beginner | Aspiring Software Developer

## Note
This project was developed by studying and understanding a reference GitHub project for learning purposes.

