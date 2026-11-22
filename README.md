# 🏥 Hospital Management System (C++)

A console-based Hospital Management System developed in C++ to streamline patient records, doctor schedules, appointment bookings, and medical billing workflows.

---

## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack & Concepts](#-tech-stack--concepts)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Contributors](#-contributors)

---

## ✨ Features

- **Patient Management**
  - Add, update, search, and delete patient records (ID, name, age, gender, diagnosis, admission status).
  - Track inpatient and outpatient histories.
- **Doctor & Staff Management**
  - Manage doctor profiles, specializations, and working shifts.
  - Assign doctors to specific patients or departments.
- **Appointment Scheduling**
  - Book, reschedule, and cancel patient-doctor appointments with conflict checking.
- **Billing & Discharge**
  - Calculate consultation fees, room charges, and medication costs.
  - Generate itemized discharge summaries and invoices.
- **Persistent Data Storage**
  - Save and load records automatically via local file handling (`.txt` / `.csv` / `.dat`).

---

## 🛠️ Tech Stack & Concepts

- **Language:** C++ (C++11 / C++17)
- **Core Concepts:**
  - Object-Oriented Programming (Encapsulation, Inheritance, Polymorphism)
  - Data Structures & Algorithms (Linked Lists / Vectors, Searching & Sorting)
  - File I/O (`fstream`) for persistent storage
  - Modular multi-file architecture (`.h` header files and `.cpp` source files)

---

## 📂 Project Structure

```text
hospital-management-system/
├── include/               # Header files (.h / .hpp)
│   ├── Patient.h
│   ├── Doctor.h
│   ├── Appointment.h
│   └── Hospital.h
├── src/                   # Source implementation files (.cpp)
│   ├── main.cpp
│   ├── Patient.cpp
│   ├── Doctor.cpp
│   ├── Appointment.cpp
│   └── Hospital.cpp
├── data/                  # Local data storage files
│   ├── patients.txt
│   └── doctors.txt
└── README.md
