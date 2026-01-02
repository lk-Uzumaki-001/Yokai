# Hospital Management App

A simple backend application for managing hospital data using **Node.js** and **Express.js**.  
This app allows you to manage **patients**, their records, and perform CRUD operations.

---

## Features

- **Patient Management** – Add, view, update, and delete patient records.
- **Doctor Management (Optional)** – Manage doctors and appointments.
- **Appointment Scheduling** – Book appointments for patients with doctors.
- **Billing & Payments (Optional)** – Calculate fees and generate bills.

---

## API Routes

### Patient Routes
| Method | Route | Description |
|--------|-------|-------------|
| GET    | /patients | Get all patients |
| GET    | /patients/:id | Get patient by ID |
| POST   | /patients | Add new patient |
| PUT    | /patients/:id | Update patient |
| PUT    | /patients | Bulk update multiple patients |
| DELETE | /patients/:id | Delete patient |

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hospital-management-app.git
