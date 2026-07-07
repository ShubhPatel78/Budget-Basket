# 🛒 Budget Basket

A console-based supermarket inventory and billing management system developed in **C++**. The project demonstrates the practical application of **Object-Oriented Programming (OOP)**, **modular software design**, and **file-based data persistence** by simulating real-world retail store operations.

---

# 📌 Overview

Budget Basket is designed to streamline supermarket operations through role-based access control and efficient inventory management. The system supports administrators, employees, and customers with dedicated functionalities for product management, billing, stock tracking, and customer management while maintaining persistent records using file handling.

The project emphasizes software engineering principles such as modularity, encapsulation, and reusable class design.

---

# ✨ Features

- 👤 Role-Based Access Control
  - Administrator
  - Employee
  - Customer

- 📦 Inventory Management
  - Add, update, delete, and search products
  - Stock monitoring
  - Automatic inventory updates after purchases

- 🏪 Vendor Management
  - Maintain vendor information
  - Associate products with vendors

- 👥 Customer Management
  - Customer registration
  - Customer information management

- 🧾 Billing System
  - Generate bills for multiple products
  - Automatic total calculation
  - Stock deduction after successful purchase

- 💾 Persistent Storage
  - File-based data management
  - Automatic record maintenance

---

# 🛠 Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Standard Template Library (STL)
- File Handling
- Git & GitHub

---

# 🏗 System Architecture

```
                User
                  │
        ┌─────────┴─────────┐
        │                   │
   Authentication      Role Selection
        │
        ▼
 ┌───────────────┐
 │ Administrator │
 ├───────────────┤
 │ Employee      │
 ├───────────────┤
 │ Customer      │
 └───────────────┘
        │
        ▼
Inventory │ Vendors │ Billing │ Customers
        │
        ▼
      Text Files
```

---

# 📂 System Modules

## 👨‍💼 Administrator

- Product management
- Vendor management
- Employee management
- Inventory maintenance

---

## 👨‍💻 Employee

- View available products
- Search products
- Update inventory
- Generate customer bills

---

## 🛍 Customer

- Registration
- Login
- Browse available products

---

# 📁 Repository Structure

```
Budget-Basket
│
├── Admin.cpp
├── Admin.h
├── Employee.cpp
├── Employee.h
├── Product.cpp
├── Product.h
├── Vendor.cpp
├── Vendor.h
├── Customer.cpp
├── Customer.h
├── main.cpp
└── README.md
```

---

# 🚀 Build and Run

### Compile

```bash
g++ *.cpp -o BudgetBasket
```

### Execute

Linux / macOS

```bash
./BudgetBasket
```

Windows

```bash
BudgetBasket.exe
```

---

# 👨‍💻 My Contributions

- Designed the object-oriented architecture of the system.
- Developed inventory and product management modules.
- Implemented customer and vendor management.
- Built the billing system with automatic stock updates.
- Integrated persistent storage using file handling.
- Tested and validated the system under multiple user scenarios.

---

# 🎯 Learning Outcomes

This project strengthened my understanding of:

- Object-Oriented Programming
- Class Design and Encapsulation
- Modular Software Architecture
- File-Based Data Persistence
- Inventory Management Systems
- Billing System Design
- Software Engineering Best Practices

---

# 🚀 Future Enhancements

- MySQL / PostgreSQL integration
- Graphical User Interface (Qt / JavaFX)
- Barcode Scanner Integration
- Sales Analytics Dashboard
- Customer Purchase History
- Receipt Printing
- Web-based Deployment
- Authentication using Password Encryption

---

# 📄 License

This project was developed for academic purposes to demonstrate object-oriented programming concepts and software design principles.
