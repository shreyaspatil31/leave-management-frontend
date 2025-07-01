# 🚀 Leave Management System – Frontend

A responsive and role-based frontend built using **React** for managing employee leave requests. Integrated with a Spring Boot backend.

## 📁 Features

- 👤 **Role-Based Access**: Admin and User dashboards
- ✅ **Login & Register** (with form validation and localStorage)
- 🗂️ **Leave Application** and History View
- 🏢 **Department Listing** (with optional Add if Admin)
- 📊 **Admin Panel** to manage and approve/reject requests
- 🔐 Protected Routes using Auth Context
- 🌐 API integration using Axios

## 🔧 Tech Stack

- **React**
- **React Router DOM**
- **Axios**
- **SweetAlert2**
- **TypeScript**
- **CSS (custom + responsive)**

## 🚦 Folder Structure

src/
│
├── components/ → Shared components (Navbar, etc.)
├── pages/ → Page components (Login, Dashboard, etc.)
├── context/ → AuthContext (for login state)
├── routes/ → ProtectedRoute logic
├── assets/ → Images and icons
└── App.tsx → Main route definitions
