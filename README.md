# Event Management System (Console-Based)

## Project Overview
This is a console-based **Event Management System** developed using **Python**.  
The application demonstrates role-based access control, membership management, maintenance, reports, transactions, validations, and session handling as per the given requirements.

This project is suitable for **Google Colab execution** and **interview demonstrations**.

---

## Features

### Authentication & Roles
- Admin login
- User signup and login
- Role-based access:
  - Admin: Maintenance, Reports, Transactions
  - User: Reports and Transactions only
- Passwords are hidden during input using `getpass`

---

### Maintenance Module (Admin Only)
- Add Membership
  - All fields are mandatory
  - Membership duration options:
    - 6 Months (default)
    - 1 Year
    - 2 Years
  - Only one option can be selected (radio button logic)
- Update Membership
  - Membership number is mandatory
  - Membership details are auto-populated
  - Options:
    - Extend membership (default 6 months)
    - Cancel membership

---

### Reports Module
- Displays membership details including:
  - Membership ID
  - Member Name
  - Membership Status
  - Validity Date

---

### Transactions Module
- Displays transaction status of memberships
- Reflects extensions and cancellations

---

### Validations
- Mandatory field validation
- Invalid membership number handling
- Duplicate user prevention

---

### Session Management
- Maintains user session during application runtime
- Proper logout functionality for Admin and User

---

## Technologies Used
- Python 3
- datetime module
- getpass module

---

## How to Run the Project

### Run on Google Colab (Recommended)
1. Open Google Colab
2. Create a new notebook
3. Paste the complete Python code into one cell
4. Run the cell
5. Follow the menu-driven interface

Note:
Radio buttons and checkboxes are implemented logically due to the console-based interface.

### Run on Local System
```bash
python event_management_system.py

