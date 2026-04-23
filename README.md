# 🎓 Student Marks Organizer (C Project)

The Student Marks Organizer is a console-based academic management system developed using the C programming language. It is designed to efficiently manage student records, calculate academic performance, and provide structured result analysis.

This project demonstrates the practical implementation of fundamental programming concepts such as data structures, sorting algorithms, file handling, and modular programming.

---

## 🚀 Key Features

- 📌 Input and manage multiple student records
- 📊 Automatic calculation of:
  - Total marks
  - Average marks
  - GPA
  - Grade
  - Pass/Fail status
- 🏆 Rank students based on performance using **Merge Sort**
- 🔍 Search students by unique ID
- ✏️ Update student marks dynamically
- 🥇 Display top-performing students
- 📈 Generate class performance statistics:
  - Highest average
  - Lowest average
  - Overall class average
- 💾 Save and load data using file handling (`students.txt`)

---

## 🧠 Algorithm Used

### 🔹 Merge Sort
- Used to rank students based on GPA
- Time Complexity: **O(n log n)**
- Ensures efficient and stable sorting for large datasets

---

## 🏗️ System Design

The program is built using structured programming principles:

- `struct Student` → Stores all student information
- Modular functions for:
  - Input handling
  - Calculation
  - Sorting
  - Searching
  - File operations

---

## 💻 Technologies Used

- C Programming Language
- Standard Libraries:
  - `stdio.h`
  - `stdlib.h`
  - `string.h`

---

## ▶️ How to Run

1. Compile the program:
```bash
gcc main.c -o program
