# Employee Management Application

## Overview
This application provides employees and administrators with a secure login system and salary details.
Employees can access their salary information based on their department and level, 
while administrators have additional privileges to manage employee records.

## Features
- **Employee Login**: Employees can log in using their username and password.
  - If the username, password, or both are incorrect, an error message is displayed.
  - If the credentials are correct, the employee gains access to the main window.

- **Main Window**:
  - Employees can select their **employee level** and **department**.
  - A textbox displays department additions and basic salary separately.
  - The **total salary** is calculated and displayed in the salary text box.
  
- **Admin Login**:
  - Admins can log in using a separate admin username and password.
  - Upon successful login, they can access salary details as employees do.
  - An additional **Admin Button** appears in the main window.

- **Admin Panel**:
  - Clicking the Admin Button grants access to an **employee information window**.
  - Admins can enter an **Employee ID** to retrieve details.
  - If the ID is incorrect, an error message appears.
  - If the ID is correct, employee details are displayed.

## Usage
1. **Employee Access**
   - Enter username and password in the login window.
   - View salary details based on level and department.

2. **Admin Access**
   - Enter admin credentials in the login window.
   - View salary details and access employee information.

## Technologies Used
- Programming Language:- C#
- IDE:- Microsoft Visual Studio



