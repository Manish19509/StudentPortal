
# Student Management System

A simple **Student Management System** implemented in **C++** to manage student records such as adding, updating, deleting, searching, and displaying all student details. The system leverages **Object-Oriented Programming (OOP)** principles for structuring student data and managing operations.

## Features

- **Add New Student**: Allows the user to input a student's roll number, name, and age, and store it in the system.
- **Display All Students**: Displays the details of all the students in the system.
- **Search Student**: Allows searching for a student based on their roll number.
- **Update Student**: Enables updating a student's details, including roll number, name, and age.
- **Delete Student**: Removes a student record from the system based on the student's name.
- **Exit**: Exits the program.

## Requirements

- **C++ compiler** (e.g., GCC, Clang)
- **Basic C++ knowledge** (for understanding the code)

## Setup

1. Clone the repository (or copy the code into your local C++ environment).
2. Compile the code using a C++ compiler. For example:
   ```bash
   g++ -o student_management student_management.cpp
   ```
3. Run the executable:
   ```bash
   ./student_management
   ```

## Usage

### Main Menu

The program will present a menu with the following options:

1. **Add New Student**: Add a new student to the system.
2. **Display All Students**: Display a list of all students in the system.
3. **Search Student**: Search for a student by roll number.
4. **Update Student**: Update the details of an existing student.
5. **Delete Student**: Delete a student from the system.
6. **Exit**: Exit the program.

### Example Interaction

```
--------------------------------
*** Student Management System ***
--------------------------------
1. Add New Student
2. Display All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
Enter Your Choice: 1
Enter Rollno: 101
Enter Name: John Doe
Enter Age: 20
Do You Want to Continue [Yes/No] ? : Y

--------------------------------
*** Student Management System ***
--------------------------------
1. Add New Student
2. Display All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
Enter Your Choice: 2

Roll No: 101
Name: John Doe
Age: 20
Do You Want to Continue [Yes/No] ? : N
```

## Code Structure

- **Student Class**: Encapsulates the student data (roll number, name, age) and provides methods to set/get these attributes.
- **Main Functions**:
  - `addNewStudent()`: Adds a new student to the system.
  - `displayAllStudents()`: Displays all student records.
  - `searchStudent()`: Searches for a student by roll number.
  - `updateStudent()`: Allows updating a student's details.
  - `deleteStudent()`: Deletes a student record from the system.

## Contributions

Feel free to fork and contribute to the project. If you have suggestions or improvements, open an issue or a pull request!

## License

This project is open-source and available under the [MIT License](LICENSE).
