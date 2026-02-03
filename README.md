# Career Trigger — FulL Stack

---

## Repository Frontend & BAckend

To explore the source code for each part of the system, please use the links below:

* **Frontend Repository:** [Career Trigger Client](https://github.com/mdabarik/career-trigger-client)
* **Backend Repository:** [Career Trigger Server](https://github.com/mdabarik/career-trigger-server)

---

## System Architecture & Principles

The entire platform is engineered with a **"Clean Code"** first mindset. Both the client and server follow industry-standard patterns:


* **Decoupled Architecture:** Frontend and Backend are completely separated, communicating through a stateless RESTful API.
* **Design Patterns:** Implementation of **SOLID**, **Singleton**, and **Layered Architecture** for better maintainability.
* **Scalability:** The backend uses a modular folder structure, allowing for easy expansion of features (YAGNI & KISS compliant).
* **Role-Based Security (RBAC):** Integrated security layer that controls access levels for Admins, Editors, and Users.

---

## 🛠️ Technical Overview

### **Backend (Node.js & Express)**
* **Database:** MongoDB via Mongoose.
* **Auth:** JWT (Access & Refresh Tokens) with Bcrypt hashing.
* **Validation:** Schema-driven validation (Zod/Joi).
* **Key Features:** Automated status updates, post analytics, and user role management.

### **Frontend (React.js & Tailwind)**
* **State Management:** Redux Toolkit for global state and RTK Query for data fetching.
* **Styling:** Utility-first CSS using Tailwind CSS for a modern, responsive UI.
* **Performance:** Code-splitting and lazy loading for optimized load times.
* **UI Experience:** Interactive dashboards, real-time input validation, and optimistic UI updates.

---

## 📁 Full-Stack

```text
career-trigger/
│
├── career-trigger-server/    # Node.js, Express, MongoDB, JWT, SOLID
└── career-trigger-client/    # React.js, Redux, Tailwind, Modular UI
