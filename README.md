# Beauty Salon Management System – University Project (Java, OOP, Swing)

This repository contains a **Beauty Salon Management System**, developed in **Java** using **Swing** as part of a **university course on Object-Oriented Programming (OOP 1)**.

The goal of the project was to gain practical experience with **OOP design**, **file-based persistence**, and **graphical user interfaces** (GUIs) using Java Swing.

## 🎯 Project Objectives

- Apply OOP principles (encapsulation, inheritance, polymorphism, etc.)
- Create a desktop application with a Swing GUI
- Handle data storage through file I/O (no database)
- Simulate real-world roles and processes of a beauty salon

## 👥 User Roles

The system supports **multiple user roles**, each with specific permissions and UI views:

- **Client** – can register, log in, book treatments
- **Beautician** – can view and manage their scheduled treatments
- **Receptionist** – can register clients, schedule treatments
- **Manager** – can view statistics, manage employees and treatments

## 💡 Key Features

- **Login and registration system**
- **Role-based access control**
- **CRUD operations** for:
  - Users (Clients, Employees)
  - Beauty treatments
  - Appointments
- **Appointment scheduling** based on availability
- **Statistics and reporting** for managerial overview
- **Persistent storage using text files**
- **GUI implemented with Java Swing**

## 🖥️ Technologies Used

- Java

## 📁 File Structure

Data is stored in local `.csv` files representing:
- Users (clients, employees)
- Treatments
- Appointments

Files are parsed on application startup and saved upon changes.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/davidstakic/beauty-salon-oop1.git
