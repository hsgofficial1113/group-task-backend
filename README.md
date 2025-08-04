
---

### ✅ BACKEND `README.md`

```markdown
# 📘 Group Task Binder - Backend

**Group Task Binder** is a powerful and intuitive task management web application built using the MERN stack (MongoDB, Express.js, React, Node.js). The backend manages authentication, data modeling, project creation, and task operations securely and efficiently.

### 🧠 What It Does:
The backend handles API requests for user authentication, project creation, and task management. It validates users using JSON Web Tokens (JWT) and stores all data in MongoDB using Mongoose models. It provides RESTful endpoints for full CRUD operations on users, tasks, and projects.

### 💻 Technologies & Code Used
The backend is built with **Node.js** and **Express.js**, following RESTful API principles. It uses **MongoDB** as the database and **Mongoose** as the ODM (Object Data Modeling) tool.

#### Key Technologies:
- **Node.js** – runtime environment
- **Express.js** – routing and middleware
- **MongoDB** – database for storing tasks, users, and projects
- **Mongoose** – schema definitions and querying
- **JWT (jsonwebtoken)** – for secure authentication
- **Bcrypt.js** – for password hashing
- **dotenv** – for managing environment variables
- **cors** and **helmet** – for added API security

#### Project Structure:
- **Routes**: API routes are defined in `/routes`
- **Controllers**: Logic for handling requests lives in `/controllers`
- **Models**: MongoDB schemas for users, tasks, and projects in `/models`
- **Middleware**: Auth middleware verifies JWT tokens for route protection

### 💡 Why Use Group Task Binder's Backend?
- Secure authentication with hashed passwords and JWT
- Modular MVC-style codebase
- CRUD functionality for tasks and projects
- MongoDB for flexible, scalable data storage
- Easy to deploy with services like Render
- Organized code separation for maintainability

---

## 🚀 Getting Started

### 📥 Clone the repository
```bash
git clone https://github.com/PhillipH04/group-task-binder.git
cd group-task-binder/backend


## 👤 Author
**Phillip Howard** — [GitHub](https://github.com/PhillipH04)