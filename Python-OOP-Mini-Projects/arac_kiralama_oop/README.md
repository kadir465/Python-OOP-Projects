# Vehicle Rental System 

A terminal-based Vehicle Rental System built with Python. This mini-project demonstrates core Object-Oriented Programming (OOP) concepts such as classes, inheritance, and method overriding. 

## Features

* **Multiple Vehicle Types:** Supports renting both cars and bikes.
* **Flexible Rental Options:** Users can rent vehicles on an hourly or daily basis.
* **Automated Billing:** Calculates the final bill dynamically using Python's `datetime` module based on the exact time the vehicle was rented and returned.
* **Discount System:** * Automatically applies a 30% family promotion discount when renting 3 to 5 vehicles.
  * Applies a 15% discount for car rentals if the total bill exceeds $100.
* **Stock Management:** Tracks available and rented inventory in real-time.

## Technologies Used

* Python 3.x
* Built-in `datetime` module

## OOP Concepts Demonstrated

This project is a great example of applying software engineering principles:
* **Inheritance:** `CarRent` and `BikeRent` classes inherit from the base `VehicleRent` class.
* **Encapsulation:** Managing stock, rental time, and basis within specific class instances.
* **Polymorphism:** Overriding methods like `rentHourly` and `rentDaily` in child classes to adapt to specific vehicle types.

## Installation and Usage

1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/kadir465/Python-OOP-Mini-Projects.git](https://github.com/kadir465/Python-OOP-Mini-Projects.git)

2. Navigate to the project directory:
   cd Python-OOP-Mini-Projects/Arac_Kiralama_Sistemi

3. Run the script:
   python araç_kiralama.py

4. Follow the on-screen interactive menu to display stock, rent vehicles, and process returns.
  
  Menu Options
Upon running the program, you will be greeted with the following interface:

1. Display available vehicles

2. Rent a car

3. Rent a bike

4. Return a car

5. Return a bike

6. Exit