# Employee Payroll System

This program is designed to manage employee information and process payroll. It utilizes a class Employee to create employee objects with attributes such as name, employee ID, position, and hourly rate. Each employee can then have their salary calculated based on the hours they've worked.

## Class Definition:

### 1. Employee:
Constructor method __init__ initializes the employee attributes.
Method calculate_salary calculates the salary based on the hours worked.
### 2. Functions:

* add_employee():

Prompts the user to input employee details.
Returns an Employee object initialized with the provided details.
* process_payroll(employees):

Takes a list of Employee objects as input.
Iterates through each employee, prompting for hours worked and calculating their salary.
* main():

Initializes an empty list for storing employee objects.
Provides a menu for user interaction:
* Add Employee: Adds a new employee to the system.
* Process Payroll: Calculates and displays payroll information for added employees.
* Exit: Terminates the program.

Handles user input and performs corresponding actions based on the choice.
### 3. Execution:

* The program starts execution from the main() function.
* User inputs are validated and appropriate actions are taken based on the chosen option.
* The program continues to run until the user chooses to exit.
