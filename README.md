# Campus Maintenance & Inspection Reporting System
**Higher-Ed Facilities Intelligence | Building Inspections | Operational Reporting**

A role-based web application built to help a university facilities team capture building inspection data digitally (instead of paper/spreadsheets) and generate reporting for operational planning. Technicians record inspection readings by building/category, and administrators manage users/buildings/categories and export reports (charts + Excel) for trend monitoring and decision support.

---

## Key Higher-Ed Use Cases
- **Campus facilities data collection** (routine building checks & condition monitoring)
- **Standardized inspections** across buildings and categories (consistent data definitions)
- **Operational KPI reporting & trends** (date-range reporting, graphs, Excel export)
- **Role-based governance** (Admin vs Technician access)
- **Exportable evidence for planning & compliance** (audit-friendly reporting)

---

## Features
### Technician
- Login and submit inspection data entries (mobile/tablet-friendly flow)
- View/update entries as allowed

### Admin
- Manage **Buildings**, **Categories**, and **Users**
- Review/edit entries for data quality control
- Generate **reports, charts, and Excel exports** by building/category/date range

---

## Tech Stack
### Backend
- **Java 17**
- **Spring Boot** (Web, Security, Data JPA)
- **Microsoft SQL Server** (JDBC driver)
- **OpenAPI/Swagger UI** (springdoc)

### Frontend
- HTML/CSS/JavaScript (multi-page UI)
- Fetch-based API integration

---

## Project Structure
- `Capstone-Project/` → Spring Boot backend (Maven wrapper included)
- `assets/` → Frontend pages, styles, and JavaScript modules

---

## Getting Started (Local Setup)

### Prerequisites
- Java **17**
- SQL Server (local) + a database created for the project
- Git

> **Security note:** Do not commit real credentials. Use environment variables or a local-only config file.

---

## Backend Setup (Spring Boot)

1) **Open the backend folder**
```bash
cd Capstone-Project

