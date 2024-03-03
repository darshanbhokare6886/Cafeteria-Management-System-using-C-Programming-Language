# Cafeteria-Management-System-using-C-Programming-Language
This project is a simple Cafeteria Management System implemented in C programming language. It allows for easy management of food items, orders, and provides functionalities for both admins and customers.

## Features
Admin Section: Admins can view total sales, add new items to the order menu, delete items from the order menu, and display the order menu.
Customer Section: Customers can place orders, view their ordered items, delete items from their order, display the final bill, and return to the main menu.
Dynamic Data Structure: The project uses a doubly linked list to manage food items and orders efficiently.
Colorful Console Output: The console output is enhanced with colored text to improve readability and user experience.
Simple User Interface: The user interface is simple and intuitive, making it easy for both admins and customers to navigate through the system.

## How to Use
Compilation: Compile the source code using a C compiler. For example, gcc main.c -o cafeteria_system.
Execution: Run the compiled executable. For example, ./cafeteria_system.
Main Menu: Choose between the admin section, customer section, or exit the program.
Admin Section: Perform admin functionalities such as viewing total sales, managing the order menu, etc.
Customer Section: Place orders, view ordered items, manage the order, and display the final bill.

## Requirements
C Compiler (e.g., GCC)
Windows Operating System (for console coloring)

## Key Concept Used in the Project:

Data Structures: The project employs a doubly linked list data structure to manage food items and orders efficiently. Each node of the linked list contains information about a specific food item, including its name, price, and quantity.

Dynamic Memory Allocation: The malloc() function is used to dynamically allocate memory for each node of the linked list. This allows for the creation of nodes at runtime, enabling the system to handle a variable number of food items and orders.

File Handling: Although not explicitly demonstrated in the provided code, file handling could be incorporated to save and load data from external files. This would enable the system to persist data between program executions, providing a more robust and user-friendly experience.

User Interface Design: The project implements a simple user interface with menu-driven interactions for both admins and customers. This enhances usability by providing a clear and intuitive way for users to navigate through the system and perform various tasks.

Modular Programming: The code is divided into separate functions, each responsible for a specific task or functionality. This modular approach enhances code readability, maintainability, and reusability, making it easier to debug and extend the system in the future.

Conditional Statements and Loops: Conditional statements (e.g., if, switch) and loops (e.g., while, for) are extensively used throughout the code to control program flow and iterate over data structures. These constructs enable the implementation of different functionalities based on user input and system state.

Function Pointers: Although not explicitly used in the provided code, function pointers could be utilized to implement more advanced features, such as custom sorting algorithms for food items or orders.

Console Output Formatting: The system uses console output formatting techniques, such as colored text and spacing, to improve the visual presentation of information and enhance the user experience.
