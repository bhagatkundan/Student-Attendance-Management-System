# Student-Attendance-Management-System

This is a command-line based Student Attendance Management System written in Python. It allows
users to manage student records and track attendance on a daily basis.

## Features
- **Add Student**: Register a new student with roll number and name.
- **Mark Attendance**: Record daily attendance as Present (P) or Absent (A).
- **View Monthly Report**: Generate a report showing the number of days each student was present
in a selected month.

## Technologies Used
- Python 3
- `datetime` module for handling dates
- `collections.defaultdict` for managing attendance records
## How to Use
1. Run the script in a Python environment.
2. Choose options from the menu to:
 - Add students
 - Mark attendance (uses today's date by default, or a custom date)
 - View monthly attendance reports
3. Exit when done.
   
## Example
```bash
--- Student Attendance Management System ---
1. Add Student
2. Mark Attendance
3. View Monthly Report
4. Exit
```
