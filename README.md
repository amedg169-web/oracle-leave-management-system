# Leave Management System (Oracle SQL)

## Project Overview
This project is a simple Leave Management System built using Oracle SQL and PL/SQL.
It simulates how companies manage employee leave requests, approvals, and leave balances.

The system includes tables, sequences, procedures, triggers, and business logic to control how leave requests are processed.

---

## Database Components

### Tables
- EMPLOYEES
- LEAVE_TYPES
- LEAVE_REQUESTS
- EMP_LEAVE_BALANCE

These tables store employee data, leave types, leave requests, and leave balances.

---

### Sequences
Sequences are used to generate automatic IDs for:

- EMPLOYEES
- LEAVE_TYPES
- LEAVE_REQUESTS
- EMP_LEAVE_BALANCE

---

### Procedures
Example procedures in this project:

**APPROVE_LEAVE**
- Approves a leave request
- Updates the request status
- Deducts the number of days from the employee leave balance

---

### Triggers
Triggers are used to enforce business rules automatically.

Example:
- Update remaining leave balance after leave approval.

---

## Business Logic
The system enforces several rules:

- Employees cannot take more leave than their available balance
- Leave requests must be approved before affecting leave balance
- Leave balance is automatically updated after approval

---

## Example Scenario

Employee: Ahmed Ali  
Leave Type: Annual Leave  
Leave Period: 01-JUN-2025 to 05-JUN-2025  
Total Days: 5  
Status: APPROVED

After approval:
- Used days increase
- Remaining balance decreases automatically

---

## Technologies Used

- Oracle SQL
- PL/SQL
- Toad for Oracle

---

## Author
Database Project created for learning Oracle SQL and PL/SQL.
