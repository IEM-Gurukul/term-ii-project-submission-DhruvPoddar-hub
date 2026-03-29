[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pG3gvzt-)
# PCCCS495 – Term II Project

## Project Title

Mini Banking System using Layered Architecture

## Problem Statement (max 150 words)

The project aims to develop a Bank Management System that allows users to perform essential banking operations such as deposit, withdrawal, balance inquiry, and fund transfer through a graphical user interface. Traditional systems often lack modularity and proper error handling, leading to unreliable transactions. This system is designed using object-oriented programming principles to ensure scalability, maintainability, and robustness. It incorporates layered architecture to separate concerns between user interface, business logic, and data management. The system also implements validation and custom exception handling to prevent invalid operations such as insufficient balance, overdraft violations, and invalid inputs. Overall, the project demonstrates how OOP concepts can be effectively used to design a reliable and user-friendly banking application.

## Target User

1. Students learning OOP concepts
2. Beginner developers
3. Users needing a simple banking simulation system

## Core Features

1. Deposit money into account
2. Withdraw money with validation
3. Transfer funds between accounts
4. Check account balance
5. GUI-based interaction using Swing
6. Error handling using custom exceptions


## OOP Concepts Used

1. Abstraction:
   Implemented using the Account abstract class
   Defines common structure for all account types
2. Inheritance:
   SavingsAccount and CurrentAccount extend Account
   Reuse common properties and methods
3. Polymorphism:
   withdraw() method overridden in both subclasses
   Different behavior for different account types
4. Exception Handling:
   Custom exceptions:
   InsufficientBalanceException
   OverdraftLimitExceededException
   AccountNotFoundException
   Ensures safe and controlled execution
5. Collections / Threads:
   HashMap used in AccountRepository to store accounts
   No multithreading used (single-threaded GUI application)

## Proposed Architecture Description

The system follows a layered architecture consisting of three main layers:

1. Presentation Layer (GUI): Handles user interaction through Swing components
2. Service Layer (BankService): Contains business logic for banking operations
3. Data Layer (AccountRepository): Manages account storage using a HashMap

## How to Run

1. Save the file as BankApplication1.java
2. Open terminal/command prompt
3. Compile the program
4. Run the program
5. Use the GUI to:
    -Enter account number
    -Enter amount
    -Perform operations using buttons

## Git Discipline Notes
Minimum 10 meaningful commits required.
