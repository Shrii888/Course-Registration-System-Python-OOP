# 🎓 Project 10 — Course Registration System

## 📌 Project Overview

The **Course Registration System** is a Python-based application developed using Object-Oriented Programming (OOP). It is designed to manage student information, course details, and course registrations through a simple menu-driven interface.

The system allows users to add students, create courses, register students for courses, drop courses, and view registration records. It also uses JSON files to automatically save and load data, ensuring that records remain available even after the program is closed.

## 🎯 Project Objectives

- Understand and implement Object-Oriented Programming concepts.
- Manage student and course information efficiently.
- Simplify the course registration process.
- Prevent duplicate student IDs and course registrations.
- Store data permanently using JSON files.
- Apply Python concepts to solve a real-world management problem.

## ✨ Features

1. **Add Students** – Add students with unique student IDs and names.
2. **Add Courses** – Create courses with unique course IDs, course names, and fees.
3. **Display Students** – View student details and the number of registered courses.
4. **Display Courses** – View available courses and their fees.
5. **Register Students** – Enroll students in available courses.
6. **Drop Courses** – Remove a course from a student's registration.
7. **Display Registrations** – View students and their registered courses.
8. **Automatic Data Saving** – Save and load records using JSON files.

## 🛠️ Technologies & Concepts Used

- **Python** – Main programming language.
- **OOP** – Classes, objects, constructors and methods.
- **Lists** – Store registered course IDs.
- **Dictionaries** – Manage student and course records.
- **Functions** – Organize different operations.
- **Loops** – Implement the menu-driven system.
- **Conditional Statements** – Handle user choices and validations.
- **JSON** – Store and retrieve data permanently.
- **File Handling** – Read and write data using files.

## 🏗️ Project Structure

```text
Project_10_Course_Registration_System/
│
├── course_registration_system.ipynb
├── students.json
├── courses.json
└── README.md
```

## 🧩 Classes Used

| Class | Description |
|---|---|
| Student | Stores student ID, name and registered courses. |
| Course | Stores course ID, course name and fee. |
| RegistrationSystem | Manages students, courses, registrations and data storage. |

## ▶️ How to Run the Project

1. Download or clone the repository.
2. Open the project folder.
3. Launch Jupyter Notebook.
4. Open `course_registration_system.ipynb`.
5. Run the complete code cell.
6. Select the required option from the menu.

**Note:** The JSON files are created automatically when data is first saved. Keep them in the same working folder as the notebook to retain your records.

## 💾 Data Persistence

The project uses two JSON files:

- `students.json` – Stores student details and registered course IDs.
- `courses.json` – Stores course details and fees.

Whenever a student or course is added, or a registration is changed, the corresponding data is automatically saved.

When the application starts again, previously saved records are loaded automatically.

## 📚 Learning Outcomes

Through this project, I practised:

- Building applications using Object-Oriented Programming.
- Creating and working with multiple classes and objects.
- Understanding the relationship between students and courses.
- Using lists and dictionaries to manage data.
- Implementing menu-driven applications using loops.
- Handling files and storing data in JSON format.
- Applying validation and error handling.

## 🚀 Future Improvements

- Add student login and administrator authentication.
- Introduce a graphical user interface (GUI).
- Integrate an SQL database such as MySQL or SQLite.
- Add course capacity and seat availability.
- Generate registration reports.
- Add search, update and delete functionality.

## 👩‍💻 Author

**Shriya Verma**

This project is part of my Python Data Analytics learning journey, where I am building practical projects to strengthen my programming, problem-solving, and logical thinking skills.

---

⭐ If you find this project useful, feel free to explore the repository!
