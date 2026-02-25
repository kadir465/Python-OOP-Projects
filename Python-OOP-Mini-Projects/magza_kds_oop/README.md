# Store Management Systems

This repository contains two Python mini-projects that demonstrate different approaches to building a console-based store management system. They showcase a progression from in-memory data structures to persistent file handling.

## Projects Overview

### 1. JSON-Based Store System (`magza_json_islemler.py`)
A comprehensive, role-based store management system that uses JSON files for data persistence. It allows user authentication and differentiates between Staff and Customer operations.

**Features:**
* **Authentication System:** Users can register and log in. The system checks credentials against local JSON files (`kullanicilar.json`, `görevli.json`).
* **Role-Based Access:** * **Staff (Görevli):** Can add new products, delete existing products, and list all inventory. Updates are saved to `urunler.json`.
    * **Customer (Müşteri):** Can search for specific products by name and ID, and purchase items (which dynamically reduces the stock in the JSON file).
* **Error Handling:** Implements `try-except` blocks to handle missing files or invalid user inputs smoothly.

### 2. List-Based Store Inventory (`magza_listesi.py`)
A simpler, object-oriented approach to managing a store's inventory using Python's built-in lists. Data is stored in memory during runtime.

**Features:**
* **Dynamic Initialization:** Users populate the store's initial inventory (product name, quantity, price) interactively upon running the script.
* **Inventory Operations:** Users can choose to update existing items (changing names, quantities, or prices) or append entirely new products to the inventory list.

## Technologies & Concepts Used

* **Python 3.x**
* **Object-Oriented Programming (OOP):** Class definitions, instance variables, and method routing.
* **File I/O:** Reading and writing `.json` files to maintain state across sessions (in the JSON version).
* **Data Structures:** Advanced list manipulations and dictionary handling.

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. To run the JSON-based system:
   ```bash
   python magza_json_islemler.py

4. To run the list-based inventory script:
  python magza_listesi.py