# inheritance_umat_management_system
# UMaT Management System

A minimalist Python implementation of the campus role management case study outlined in `image.png`. This project serves as a clean demonstration of core Object-Oriented Programming (OOP) concepts.

---

##  Core OOP Architecture

*   **Inheritance:** `Student` and `Lecturer` child classes inherit shared attributes (`name`, `age`) from a base `Person` parent class.
*   **Super Initialization:** Uses `super().__init__()` to cleanly pass arguments up to the parent constructor.
*   **Method Overriding:** The `Student` class overrides `display_info()` to append unique IDs while preserving parent logic via `super()`.
