# CACVi-UN — Violence Incident Reporting Platform

A project by Universidad Nacional de Colombia – Ingeniería de Software 2

## 🚀 Overview

**CACVi-UN** is a reporting and visualization platform designed for the Universidad Nacional de Colombia (Bogotá campus). It allows students, staff, and community members to report incidents of violence and visualize them on an interactive map.

The system enhances campus safety by providing:

- A standardized channel for reporting violence
- Real-time incident visualization
- Tools for administrators to manage and analyze reports

## 📂 Repositories

### 🔹 Frontend (React + Typescript + Leaflet)
👉 [https://github.com/jumontenegrol/cacviun.git](https://github.com/jumontenegrol/cacviun.git)

### 🔹 Backend (Node.js + TypeScript + NestJS + MongoDB)
👉 [https://github.com/Emontanor/cacviun-backend.git](https://github.com/Emontanor/cacviun-backend.git)

## 🎯 Purpose

Violence — especially gender-based violence — occurs frequently on campus, yet victims often lack an accessible, centralized place to report it.

**CACVi-UN aims to:**

- Provide a simple, secure reporting mechanism
- Offer clear visualization of incident distribution
- Support future institutional initiatives and research
- Strengthen transparency and community awareness

## 👥 Roles

### User

- Registers with a UNAL institutional email
- Submits incident reports
- Views their personal report history
- Views the interactive incident map

### Administrator

- Can view all reports
- Can edit or delete any report
- Can register new administrators

## 📌 Features

### 🔐 Authentication

- Login with institutional email
- Password recovery
- Secure hashing and storage

### 📝 Incident Reporting

Reports include:

- Victim information
- Date of incident
- Type of violence
- Description
- Zone of the campus

All sensitive data stored with confidentiality.

### 🗺️ Interactive Map

- Map of the Bogotá campus
- Markers representing incidents
- Admin view with global access

### 📚 User Report History

- Users view and delete their own reports

### 🛠️ Admin Dashboard

- Manage incidents
- Manage administrator accounts

## 🧱 Domain Concepts

### Types of Violence

- Physical
- Sexual
- Psychological
- Workplace violence
- Discrimination

### Campus Zones

Includes more than 40 zones such as:

- Medicina
- Derecho
- IPARM
- Laboratorios de Ingeniería
- Museo de Arquitectura
- Plaza Che
- Invernaderos
- Hemeroteca
- …and many more

## 🧑‍💻 Development Team (Group Lolas VIP)

- **Juan David Serrano Ruiz** — Scrum Master
- **Juan David Montenegro López** — Frontend Lead
- **Federico Hernández Montaño** — Backend Lead
- **Felipe Rojas Marín** — Testing Lead
- **Diego Esteban Ospina Ladino** — Data Analyst

## 🧱 Architecture

### Frontend

- React
- TypeScript
- Jest
- Leaflet.js
- GitHub Pages

### Backend

- Node.js
- NestJS
- TypeScript
- MongoDB
- MailerSend

## 📜 License

This project is developed for academic purposes under the course **Ingeniería de Software 2** – Universidad Nacional de Colombia.

---

*For more information, please refer to the [Documentation](./Documentation) folder.*
