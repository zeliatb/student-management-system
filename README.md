# student-management-system
This is a capstone project for the **RITA Africa Python Fundamentals Course**, designed to manage student records efficiently. This system features secure user authentication, full CRUD operations for student data, activity logging, and report generation, all backed by simple file-based storage.

## Key Features
- **Authentication System** – Secure login system using 'getpass' with user accounts stored in 'users.txt'
- **Student Data Management** – Add, view, search, update, and delete student records
- **Report Generation** – Generate basic reports on total students and grade distribution
- **Activity Logging** – Tracks user logins, logouts, and actions in 'activity_log.txt' with timestamps
- **File-Based Storage** – Data is stored in text files ('students.txt', 'users.txt') for persistence

## Technologies Used
- Python 3.x
- File Handling (TXT)
- Datetime module (for logging timestamps)
- Getpass module (for hidden password entry)

## Project Structure
student_management_system/
- main.py            # Main program with menu-driven interface
- users.txt          # Stores usernames and passwords
─ students.txt       # Stores student records
─ activity_log.txt   # Logs user activity

### How to Run
1. Clone this repository:
   git clone https://github.com/zeliatb/student-management-system.git
   cd student-management-system
2. Run the program:
   python main.py
3. If running for the first time, create an Admin account when prompted

### Usage
1. Login with a valid username and password.
2. Use the menu to:
    - Add a new student
    - View all students
    - Search for a student by roll number
    - Update student details
    - Delete student records
    - Generate a report
3. Logout when finished - your session activity will be logged.

### Sample Report Output
**Student Report**
- Total Students: 8
  - Grade A: 3 student(s)
  - Grade B: 3 student(s)
  - Grade C: 1 student(s)
  - Grade D: 1 student(s)

### Acknowledgements
This project was developed as part of the **RITA Africa Python Fundamentals Course**. Special thanks to the Educator, Python Instructor, and fellow learners who have made this journey meaningful so far.
