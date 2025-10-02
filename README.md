# Design Pattern Implementations & Satellite Command Control System

This repository contains **Java implementations** of various design patterns and a **Satellite Command Control System**. The exercises demonstrate how design patterns can solve real-world problems by providing structured, reusable, and maintainable code.  

Patterns are categorized into **Creational**, **Behavioral**, and **Structural**, and are applied to practical use cases.  

The **Satellite Command System** combines multiple patterns to manage operations like rotation, panel management, and data collection efficiently, while providing **undo functionality** and **activity logging**.

---

## Exercise 1: Design Pattern Implementations

### Creational Patterns
- **Singleton (TV Remote)** – Ensures only one remote instance exists for TV control.  
- **Factory Method (Car Manufacturing)** – Creates different car types via factories, decoupling creation from client code.  

### Behavioral Patterns
- **Observer (Social Media Influencer)** – Automatically notifies followers when new content is posted.  
- **Strategy (Sorting Algorithms)** – Allows runtime switching of sorting algorithms without changing client code.  

### Structural Patterns
- **Composite (Leave Approval System)** – Handles individual and group approvers uniformly in hierarchical leave approvals.  
- **Facade (Online Store System)** – Simplifies interactions between inventory, payment, and shipping subsystems.  

---

## Exercise 2: Satellite Command Control System

A **Java-based system** simulating ground control of a satellite. It demonstrates design pattern usage for managing satellite operations efficiently.

### Design Patterns Used
- **Singleton (Satellite)** – Ensures only one satellite instance exists.  
- **Command Pattern** – Encapsulates operations (rotate, panel control, data collection) with **undo functionality**.  
- **Observer Pattern** – Logs satellite state changes automatically to file.  

### Functionalities
- Satellite rotation  
- Solar panel management  
- Data collection  
- Undo operations  
- Status monitoring  
- Activity logging
