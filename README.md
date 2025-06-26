# 🎓 Student Grade Tracker GUI

A desktop application built with Java Swing that allows users to manage and analyze student grades easily. Add, delete, sort, search, and export student grade data with a clean, user-friendly graphical interface.

## ✨ Features

- ✅ Add student name and grade
- ❌ Delete student by name
- 🔍 Search for a student
- 🔃 Sort students by grade or name
- 📊 View average, highest, and lowest grades
- 💾 Export summary to `student_summary.txt`

## 🖼️ GUI Overview

- Input fields for **student name** and **grade**
- Action buttons for adding, deleting, searching, sorting, and exporting
- Text area displays student list and summary report

## 🛠️ How to Run

### 📦 Requirements

- Java Development Kit (JDK 8 or later)
- An IDE (like IntelliJ, Eclipse, or VS Code) **or** terminal/command prompt

### ▶️ Running the App

1. Clone or download the repository.

2. Compile and run:

```bash
javac StudentGradeTrackerGUI.java
java StudentGradeTrackerGUI
Student Grades:
Alice                 95.00
Bob                   88.50

--- Summary ---
Average Grade: 91.75
Highest Grade: 95.00
Lowest Grade: 88.50
📁 Project Structure
StudentGradeTracker/
│
├── StudentGradeTrackerGUI.java   # Main Java source code
├── student_summary.txt           # Exported file (generated at runtime)
└── README.md                     # Project description


