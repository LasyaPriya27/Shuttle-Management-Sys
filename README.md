# 🚀 ShuttleInSync - Book. Board. Be There.

A full-stack Shuttle Management System built with MERN (MongoDB, Express, React, Node.js). It includes student and admin authentication, shuttle bookings, wallet management, and an admin dashboard.

![Shuttle System UI](![image](https://github.com/user-attachments/assets/719a9c58-8a1e-4c03-b880-928269b4c06c)
)

---

## 🎥 Live Demo Video

📽️ [Watch Demo Video Here](https://drive.google.com/file/d/1chkLfB_2XthdswzYaCj7dMPgfgF4tZnd/view?usp=sharing)

---

## 📦 Features

### 👩‍🎓 For Students
- Sign up / Login
- Wallet balance view
- Browse and book available shuttles
- View past bookings

### 🧑‍💼 For Admin
- Login as Admin
- View all students & wallets
- Create and manage shuttle routes
- Recharge student wallets
- View all bookings
- View total revenue & booking statistics

---

## 🖼️ UI Previews

Login Page | Book Shuttle | My Bookings |
|------------|--------------|-------------|
| ![login](https://github.com/user-attachments/assets/fa21fb62-fd51-43fc-8c62-030fb567f066) | ![shuttles](https://github.com/user-attachments/assets/b27f17d7-1c97-43dc-ab76-4cf5da3b1d4d) | ![bookings](https://github.com/user-attachments/assets/7216b4b2-f5d4-4392-b579-42ebdf0a02b1) |

### 🧑‍💼 Admin Views
| Admin Panel | Manage Shuttles | Recharge Wallet |
|-------------|------------------|------------------|
| ![admin](https://github.com/user-attachments/assets/bc5867f8-6394-4c1c-9217-2654c8b03d81) | ![manage](https://github.com/user-attachments/assets/97358b29-377d-4602-8be4-86c6f63752ec) | ![recharge](https://github.com/user-attachments/assets/64a31dee-5990-451e-b5ec-b6b270ebd824) |

---

## 🧰 Tech Stack

- ⚙️ Backend: Node.js, Express
- 📊 Database: MongoDB (local or Atlas)
- 🎨 Frontend: React + Tailwind CSS
- 🔐 Auth: JWT
- 📦 Deployment: Render (backend) + Vercel (frontend)

---

## 🚀 Getting Started

### 📁 Folder Structure
```
shuttle/
├── shuttle-frontend/   # React app
├── shuttle-backend/    # Express + MongoDB API
```

### 1️⃣ Install MongoDB (locally or via MongoDB Atlas)
- [MongoDB Download](https://www.mongodb.com/try/download/community)
- Default URI for local: `mongodb://localhost:27017/shuttle`

### 2️⃣ Backend Setup (shuttle-backend)

```bash
cd shuttle-backend
npm install
```

🔑 Create `.env` file:
```
MONGO_URI=mongodb://localhost:27017/shuttle
JWT_SECRET=supersecretkey
```

▶️ Start backend:
```bash
npx nodemon server.js
```

### 3️⃣ Frontend Setup (shuttle-frontend)

```bash
cd shuttle-frontend
npm install
```

🧪 Create `.env` file:
```
REACT_APP_API_URL=http://localhost:5000/api
```

▶️ Start frontend:
```bash
npm start
```

Frontend will open at http://localhost:3000 🚀

---

## 🔐 Default Roles

| Email                    | Password | Role    |
|--------------------------|----------|---------|
| admin@example.com        | admin123 | Admin   |
| student1@example.com     | stud123  | Student |

✏️ You can create new accounts via Signup page.

---

## ☁️ Deployment Guide

### 🔧 Backend on Render
- Create web service → point to `shuttle-backend`
- Set environment variables in Render:
  - MONGO_URI
  - JWT_SECRET
- Set build/start commands:
  ```
  npm install
  node server.js
  ```

### 🌐 Frontend on Vercel
- Import GitHub repo → select `shuttle-frontend`
- Add Vercel env var:
  ```
  REACT_APP_API_URL=https://<your-backend-on-render>.onrender.com/api
  ```

---

## 👨‍💻 Author
Developed by [@lasyapriya](https://github.com/LasyaPriya27)

---
