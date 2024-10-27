Requirement Document for Employee Management System

1. Project Overview

The objective of this project is to build a web application to manage employee records using modern web technologies. The front end will be developed with Angular, the back-end API will be implemented using .NET Core, and Microsoft SQL Server will serve as the database. The application will allow the company to manage employee information efficiently, with flexibility to accommodate future growth.


2. Functional Requirements

2.1 Employee Data Capture

The following information must be captured for each employee: First Name, Last Name, Date of Birth, Address and Department

2.2 Department Management

Display a dropdown of departments when adding an employee.
Departments are initially limited to Finance, HR, IT, and Sales.
The system should allow adding new departments without modifying the codebase (e.g., storing departments in the database).


3. UI Requirements

3.1 Home page 
Display a list of Employee Names and a link to the “Add Employee” page.

3.2 Add employee page
The page will have a form that will capture the employee data mentioned in the functional requirements, with a drop-down to select the department. The address can be captured in a single text field. 
