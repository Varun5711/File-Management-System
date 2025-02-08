# File Management System in C++

## Overview
This project is a **File Management System** developed in C++ that allows administrators to manage products and customers to generate invoices. It provides functionalities like product creation, modification, deletion, and billing.

## Features
- **Product Management**  
  - Add, modify, delete, and display products.
  - Stores product details (ID, Name, Rate) in a file.

- **Billing System**  
  - Customers can select products and specify quantities.
  - Generates an invoice with total amount.

- **User Roles**  
  - Administrator: Manages products.
  - Customer: Purchases products and generates bills.

- **File Handling**  
  - Uses file operations (`fstream`) to store and retrieve data.

- **Interactive CLI Interface**  
  - Provides a structured menu for easy navigation.

## How to Use
1. **Run the Program**  
   Compile and execute the `main()` function.
   
2. **Select User Role**  
   - Choose between Customer or Administrator.

3. **Admin Functionalities**  
   - Create, modify, delete, and display products.

4. **Customer Functionalities**  
   - View products, add to cart, and generate an invoice.

## Project Structure
├── main.cpp       # Main source file
├── Products.txt   # Stores product data
├── README.md      # Project documentation

## Future Enhancements
- Add database support for better scalability.
- Implement a graphical user interface (GUI).
- Enhance product search functionality.

## Technologies Used
- **C++**: Core programming language.
- **File Handling**: For data storage.
- **OOP Concepts**: Used classes and objects for modular design.

## Author
Developed by **Varun Hotani** and contributors.