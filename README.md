# MotorPH Payroll System

A Java-based payroll system developed in NetBeans for the MotorPH payroll milestone/project requirements.

## Project Description

This program reads employee and attendance data from CSV files and processes payroll based on the required rules. It uses a single Java file and avoids OOP-based multi-file design to comply with the project instructions.

The system supports two user roles:

- `employee`
- `payroll_staff`

## Features

- Login system with required username and password
- Employee view for checking employee details
- Payroll staff view for processing payroll
- Reads data from:
  - `employees.csv`
  - `attendance.csv`
- Displays records from **June to December**
- Separates payroll into:
  - **1st cutoff** (1–15)
  - **2nd cutoff** (16–end of month)
- Computes total hours worked based only on **8:00 AM to 5:00 PM**
- Excludes extra hours/overtime from payroll computation
- Computes gross salary, deductions, and net salary
- Uses only **one Java file** as required

## Login Credentials

### Valid Usernames
- `employee`
- `payroll_staff`

### Password
- `12345`

## How the Program Works

### 1. Login
The program first asks for a username and password.

If the credentials are incorrect, it displays:

```text
Incorrect username and/or password.
