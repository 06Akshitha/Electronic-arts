# Electronic-arts
# Inventory Management System
This is a simple **Inventory Management System** implemented in C++. It allows users to:
Add items** to the inventory.
Sell items** and update stock.
List all available items** in the inventory.

The program follows a **menu-based system**, making it easy for users to interact with and manage their inventory.

Features

User-Friendly Interface
- A menu-driven approach for easy navigation.
- Intuitive prompts guide users through actions.

 Object-Oriented Programming (OOP) Design
- **Encapsulation**: Uses `Item` and `Inventory` classes to keep the code organized.
- **Modular Structure**: Separation of concerns makes it easy to maintain and expand.

Efficient Data Management
- Uses **`std::unordered_map<std::string, Item>`** for quick item lookups (**O(1) complexity**).
- Avoids memory leaks by using standard C++ containers instead of raw pointers.

 Smart Inventory Updates
- If an item is **already in inventory**, it **updates the quantity** instead of creating duplicates.
- Automatically **removes items** when their quantity reaches zero.

Basic Error Handling
- Ensures that users **cannot sell more than the available stock**.
- Provides warnings when trying to sell non-existent items.

Installation & Usage

Requirements
- C++ Compiler (GCC, Clang, MSVC, etc.)
- Any IDE or terminal to run the program


Future Improvements
1.Enhanced Input Validation** – Improve error handling for invalid inputs.  
2.Save & Load Inventory** – Implement file I/O to persist data between runs.  
3.Better User Experience (UX)** – Show available stock before selling, display total earnings, and more.  

Conclusion
This Inventory Management System is a great example of **object-oriented programming** and **efficient data handling** in C++. It ensures clean memory usage and quick inventory lookups while maintaining a simple and user-friendly design.
