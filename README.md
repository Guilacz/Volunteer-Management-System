# Volunteer Management System

A desktop application developed in C# and .NET for managing volunteers and educational assistance requests.

This was my first C#/.NET desktop application, developed with another student as an academic project. We focused on layered architecture, business logic, and XML data storage, with a functional WPF interface.

## Screenshots

<img width="1062" height="831" alt="Capture d&#39;écran 2026-10-18 153027" src="https://github.com/user-attachments/assets/6fc03ef9-9e2b-4a5a-8a6a-08c636c71687" />
<img width="858" height="667" alt="Capture d&#39;écran 2026-10-18 153115" src="https://github.com/user-attachments/assets/ec93aa82-01d5-4015-be3e-58bae9f27ab6" />
<img width="1060" height="817" alt="Capture d&#39;écran 2026-10-18 153211" src="https://github.com/user-attachments/assets/54ea7837-1748-410f-93c2-90a445b3c446" />



## 📌 About the Project

The application provides a system for managing volunteers and assistance requests.

It separates the user interface, business logic, and data access into independent layers, making the application easier to maintain and extend.

## ✨ Main Features

- Volunteer management
- Assistance request management
- Manager and volunteer interfaces
- Assignment of volunteers to requests
- Data persistence using XML
- Business logic separated from the presentation layer
- Desktop graphical interface using WPF and XAML
- Support for asynchronous operations
- Automated tests for business and data-access layers

## 🏗️ Architecture

The project follows a multi-layer architecture:

**Presentation Layer (PL)**  
WPF/XAML desktop user interface.

**Business Logic (BL)**  
Contains the application's business rules and operations.

**Data Access Layer (DAL)**  
Responsible for storing and retrieving application data.

The project includes multiple DAL implementations, including XML and in-memory data storage.

## 🛠️ Technologies

- C#
- .NET 8
- WPF
- XAML
- XML
- LINQ
- Git & GitHub

## 👥 Team

Academic project developed by two students.

## 🎓 Purpose

The project was created as part of our software development studies to practice object-oriented programming, layered architecture, data persistence, testing, and desktop application development.

## Getting Started

### Requirements
- Windows
- Visual Studio with the .NET desktop development workload
- .NET 8 SDK

### Run the application
1. Download or clone this repository.
2. Open `dotNet5785_9837_4238/dotNet5785_9837_4238.sln` in Visual Studio.
3. Set `PL` as the startup project.
4. Press F5 to run.

### Demo manager account
- ID: `147142541`
- Password: `check@yes`

After logging in, select Yes to open the manager dashboard.

All included sample data is fictional.
