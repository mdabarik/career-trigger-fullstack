# Career Trigger — Full Stack

---

## Repository Frontend & Backend

To explore the source code for each part of the system:

* Frontend: https://github.com/mdabarik/career-trigger-client
* Backend:  https://github.com/mdabarik/career-trigger-server

---

## System Architecture & Principles

* Decoupled Architecture: Frontend & Backend separated, RESTful API communication
* Design Patterns: SOLID, Singleton, Layered Architecture
* Scalability: Modular folder structure (KISS & YAGNI)
* Role-Based Security (RBAC): Admin, Editor, User access control

---

## Technical Overview

### Backend (Node.js & Express)
* Database: MongoDB (Mongoose)
* Auth: JWT (Access & Refresh) + Bcrypt
* Validation: Zod / Joi
* Features: Status automation, post analytics, role management

### Frontend (React.js & Tailwind)
* State: RTK Query
* Styling: Tailwind CSS (utility-first)
* Performance: Code-splitting, lazy loading
* UI: Interactive dashboards, real-time validation, optimistic updates

---

## Full-Stack Structure

``` bash
career-trigger/
│
├── career-trigger-server/    # Node.js, Express, MongoDB, JWT, SOLID
└── career-trigger-client/    # React.js, Redux, Tailwind, Modular UI
```
