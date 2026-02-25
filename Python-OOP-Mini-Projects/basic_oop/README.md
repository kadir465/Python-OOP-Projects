# Basic OOP Concepts in Python

This folder contains introductory mini-scripts that demonstrate the fundamental principles of Object-Oriented Programming (OOP) in Python. Each file focuses on different core concepts.

## Files and Concepts

### 1. `oop.py` (Abstraction & Encapsulation)
Calculates the area and perimeter of geometric shapes. 
* **Concepts Demonstrated:**
  * **Abstract Base Classes (ABC):** Uses the `abc` module to create a blueprint `Sheap` class with `@abstractmethod`.
  * **Encapsulation:** Uses private variables (e.g., `__radius`, `__side`) to protect data from direct external modification.
  * **Polymorphism & Method Overriding:** The `Circle` and `Square` classes implement their own specific versions of `area()`, `perimeter()`, and `toString()`.

### 2. `inheritance_example.py` (Inheritance)
Simulates user registration for different website tiers.
* **Concepts Demonstrated:**
  * **Inheritance:** `Website2` and `Website3` classes inherit fundamental attributes (name, surname) from the base `Website` class.
  * **`super()` Function:** Reuses the initialization logic of the parent class while adding new specific attributes like `age` or `mail`.

### 3. `first_app.py` (Classes & Objects)
A simple terminal application to register and list football players.
* **Concepts Demonstrated:**
  * **Class Instantiation:** Dynamically creating multiple `Footballer` objects based on user input.
  * **Object Storage:** Appending class instances to a Python list and iterating over them to display attributes like name, number, and club.

### 4. `islemler.py` (Methods & State Management)
A dynamic calculator that stores user inputs in an array and performs basic arithmetic operations.
* **Concepts Demonstrated:**
  * **State Management:** Maintaining a list (`self.dizi`) within the class instance.
  * **Control Flow:** Routing user choices to specific class methods (`topla`, `cikar`, `carp`, `bol`) for execution.

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/kadir465/Python-OOP-Mini-Projects.git](https://github.com/kadir465/Python-OOP-Mini-Projects.git)

2. Navigate to this directory:
cd Python-OOP-Mini-Projects/basit_oop

3. Run any of the scripts using Python:
python oop.py