# Leave Management System (Oracle SQL & PL/SQL)

This project is a simple Leave Management System built using Oracle Database.

## Features

- Employee leave balance tracking
- Leave request submission
- Automatic leave balance validation
- Leave approval system
- Reporting using SQL Views

## Technologies Used

- Oracle SQL
- PL/SQL
- Triggers
- Stored Procedures
- Constraints
- Views

## Database Structure

Tables:

- LMS_EMPLOYEES
- LMS_LEAVE_TYPES
- LMS_EMP_LEAVE_BALANCE
- LMS_LEAVE_REQUESTS

## Business Logic

### Trigger
Validates employee leave balance before inserting a leave request.

### Procedure
Approves leave requests and updates employee leave balance.

## Example Flow

1. Employee submits leave request
2. Trigger checks available balance
3. Manager runs procedure to approve leave
4. Leave balance updates automatically

## Author

Ahmed