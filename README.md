# 🚗 Car Rental Management System

## 📌 Project Overview

The **Car Rental Management System** is a software application designed to automate and manage the operations of a car rental company. It enables efficient handling of customers, vehicles, reservations, payments, and administrative processes.

This project is developed using **Object-Oriented Programming (OOP)** principles to ensure modularity, scalability, and maintainability.

---

## 🎯 Objectives

* Simplify car rental operations
* Manage customer data efficiently
* Track vehicle availability and status
* Automate booking and reservation processes
* Handle billing and payments
* Improve overall system reliability

---

## 🧠 System Features

### 👤 Customer Management

* Add, update, and delete customer records
* Store personal information (name, contact, license, etc.)
* View customer rental history

### 🚘 Vehicle Management

* Add and manage vehicle details
* Track availability status (Available / Rented / Maintenance)
* Categorize cars (SUV, Sedan, etc.)

### 📅 Reservation System

* Book cars based on availability
* Manage rental dates (start/end)
* Cancel or modify reservations

### 💳 Payment Management

* Calculate rental cost
* Process payments
* Generate invoices

### 🧑‍💼 Admin التحكم

* إدارة المستخدمين
* عرض التقارير
* التحكم الكامل بالنظام

---

## 🏗️ System Architecture (OOP Design)

The system is built using core OOP concepts:

* **Encapsulation**: Protecting class data
* **Inheritance**: Reusing base class features
* **Polymorphism**: Flexible method behavior
* **Abstraction**: Hiding implementation details

---

## 🧩 Main Classes

### 1. Customer

**Attributes:**

* customerId
* name
* phone
* email
* licenseNumber

**Methods:**

* registerCustomer()
* updateCustomer()
* deleteCustomer()
* viewHistory()

---

### 2. Car

**Attributes:**

* carId
* model
* brand
* year
* status
* pricePerDay

**Methods:**

* addCar()
* updateCar()
* removeCar()
* checkAvailability()

---

### 3. Reservation

**Attributes:**

* reservationId
* customer
* car
* startDate
* endDate

**Methods:**

* createReservation()
* cancelReservation()
* calculateCost()

---

### 4. Payment

**Attributes:**

* paymentId
* reservation
* amount
* paymentDate

**Methods:**

* processPayment()
* generateReceipt()

---

### 5. Admin

**Attributes:**

* adminId
* username
* password

**Methods:**

* manageUsers()
* generateReports()

---

## 🔗 Relationships Between Classes

* Customer ↔ Reservation (One-to-Many)
* Car ↔ Reservation (One-to-Many)
* Reservation ↔ Payment (One-to-One)
* Admin ↔ System (Control Relationship)

---

## 🗂️ Database Design (Conceptual)

### Tables:

* Customers
* Cars
* Reservations
* Payments
* Admins

Each table is linked using primary and foreign keys to ensure data integrity.

---

## ⚙️ Technologies Used

* Java (OOP)
* UML (System Design)
* Database (MySQL / SQL)

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/car-rental-system.git
```

2. Open the project in your IDE (IntelliJ / Eclipse / NetBeans)

3. Configure database connection

4. Run the main class

---

## 📊 Use Case Scenario

A customer wants to rent a car:

1. Customer registers in the system
2. Customer searches for available cars
3. Selects a car and rental period
4. System creates reservation
5. Payment is processed
6. Car status changes to "Rented"
7. After return, status updates to "Available"

---

## 📈 Future Improvements

* Add GUI (JavaFX / Swing)
* Online booking integration
* Mobile application support
* Advanced analytics dashboard

---

## 👨‍💻 Developers

* Nadeem Mansour Hassan Albana
* Ghyth Ghilan
* Mohammed Monwer Al-Tebihi
* Asim Hezam Al-Sarawi
* Abdullah Amin Mohammed Ahmed
* Mohammed Yusuf

---

## 📄 License

This project is for educational purposes only.

---

## ⭐ Support

If you like this project, give it a star ⭐ on GitHub!
