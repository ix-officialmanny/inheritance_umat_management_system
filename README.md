# Inheritance_Umat_Management_System

This project serves as a clean demonstration of core Object-Oriented Programming (OOP) concepts. A minimalist Python implementation of UMaT campus role management.

---

##  Core OOP Architecture

*   **Inheritance:** `Student` and `Lecturer` child classes inherit shared attributes (`name`, `age`) from a base `Person` parent class.
*   **Super Initialization:** Uses `super().__init__()` to cleanly pass arguments up to the parent constructor.
*   **Method Overriding:** The `Student` class overrides `display_info()` to append unique IDs while preserving parent logic via `super()`.
