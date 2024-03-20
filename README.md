# A3
Assigment 3 Q1

# Student Management Application

This application connects to a PostgreSQL database to perform CRUD operations on a 'students' table.

# Running the Application

1. Update Database Connection Information:**
   - Open the student_management.py file in a text editor.
   - Replace `"your_username"` and `"your_password"` in the `connect_to_db()` function with your PostgreSQL username and password.

2. Run the Application:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing the student_management.py file.
   - Run the application by executing the following command:
     ```
     python student_management.py
     ```

# Application Functions

- `getAllStudents()`: Retrieves and displays all records from the students table.
- `addStudent(first_name, last_name, email, enrollment_date)`: Inserts a new student record into the students table.
- `updateStudentEmail(student_id, new_email)`: Updates the email address for a student with the specified student_id.
- `deleteStudent(student_id)`: Deletes the record of the student with the specified student_id.
