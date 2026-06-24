# Project Management Tool

A full-stack Project Management Tool built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This application helps teams manage projects efficiently by allowing administrators to create projects, assign tasks, monitor progress, and track completion while enabling members to manage and update their assigned work.

---

## Live Demo & Source Code

- **Live Website:** [Visit Live Site](https://project-management-system-058.netlify.app)
- **GitLab Repository:** [View Source Code](https://gitlab.com/abhishekmevada/project-management-system)

---

## Features

### Authentication
* User Registration and Login
* JWT Authentication with Password Encryption (bcrypt)
* Role-Based Access Control (Admin & Member)

### Admin Features
* Create, edit, and delete projects
* Add team members and assign tasks to members
* View, open, and monitor every assigned task details
* View overall project statistics and track task progress

### Member Features
* View assigned tasks and project details
* Read task descriptions and check deadlines
* Update task status and track personal task progress

---

## Task Management

Each task contains:
* Title & Description
* Project Name
* Assigned Member & Created By
* Priority (Low / Medium / High)
* Status (Pending / In Progress / Complete)
* Deadline & Created Date

---

## Project Tracking

The dashboard automatically tracks:
* Total Projects & Total Tasks
* Completed, Pending, and In Progress Tasks
* Project Completion Percentage

Project status is calculated automatically based on progress:

| Completion | Status |
| :--- | :--- |
| 0% | Not Started |
| 1–99% | In Progress |
| 100% | Completed |

---

## Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React.js, React Router, Axios, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT (JSON Web Token), bcrypt |
| **Tools** | GitHub (Version Control), Postman (API Testing) |

---

## Project Structure

```text
project-management-tool/
│
├── client-side/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server-side/
│   ├── db/
│   ├── package.json
│   └── index.js
│
└── README.md
```

---

## Author

**Abhishek Vimal Mevada**

**Frontend Developer | React.js Developer | JavaScript | HTML | CSS | Tailwind CSS | Bootstrap | MERN Stack Enthusiast**
