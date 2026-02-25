# School Management System

A terminal-based Python application designed to manage school records, grades, and user roles. This mini-project demonstrates how to implement role-based access control and handle data persistence using standard text (`.txt`) files.

## Features & Role-Based Access

The system divides functionalities based on three distinct user roles:

* **1. Admin (Görevli):**
  * Registers new students.
  * Views the complete list of registered students.
  * Updates existing student records.
  * Deletes student records.
  * *Data is persistently stored in `ogrenci.txt`.*

* **2. Teacher (Öğretmen):**
  * Inputs grades for specific students.
  * Views the complete list of all student grades.
  * *Data is persistently stored in `notlar.txt`.*

* **3. Student (Öğrenci):**
  * Can query and view their own grades securely by entering their unique student ID.

## Technologies & Concepts Used

* **Python 3.x**
* **Object-Oriented Programming (OOP):** Class-based structure for different user roles (`OkulSistem`, `Gorevli`, `Ogretmen`, `Ogrenci`).
* **File I/O:** Reading, appending, and overwriting standard text files to maintain data between sessions.
* **Error Handling:** Extensive use of `try-except` blocks to prevent crashes from `ValueError` (invalid menu inputs) and `FileNotFoundError` (missing data files).

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the application using the terminal:
   ```bash
   python okul_takip_sistemi.py

4. Follow the interactive prompts to select your role and perform actions.
Note: The system will automatically create ogrenci.txt and notlar.txt files in the same directory upon your first data entry.