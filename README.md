# PRODIGY_FS_05

# 🌐 MERN Social Media Platform (Task-05)

## 📌 Internship Task
This project is submitted for **Task-05: Social Media Application Development** under Prodigy Infotech Internship.

---

## 🚀 Project Overview
This is a full-stack **Social Media Web Application** built using the MERN stack.

Users can create accounts, share posts, and interact with other users through likes and comments, simulating a real-world social networking platform.

---

## ✨ Features

### 👤 User Authentication
- Secure user registration and login
- JWT-based authentication
- Protected routes

### 📝 Posts & Feed
- Create and share posts
- View posts from other users
- Dynamic feed system

### ❤️ Social Interaction
- Like posts
- Comment on posts
- Real-time engagement

### 🔄 Real-Time Features
- Socket-based communication (if implemented)
- Live updates for interactions

---

## 🧩 Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Other Tools
- Socket.io (for real-time features)
- JWT Authentication

---

## 📂 Project Structure
```
/backend → Node.js API & server
/frontend → React frontend (Vite)
/models → Database schemas
/routes → API routes
/controllers → Business logic
/socket → Real-time communication
```

---

## ⚙️ How to Run the Project

### 🔹 1. Clone the Repository
```
git clone <your-repo-link>
cd MERN-SOCIAL
```

---

### 🔹 2. Setup Backend

```
cd backend
npm install
```

Create a `.env` file inside `backend`:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:
```
npm start
```
or
```
npm run dev
```

---

### 🔹 3. Setup Frontend

Open a new terminal:

```
cd frontend
npm install
npm run dev
```

---

### 🌐 4. Run Application

Frontend:
```
http://localhost:5173
```

Backend:
```
http://localhost:5000
```

---

## 📸 Screenshots

<img width="1257" height="524" alt="image" src="https://github.com/user-attachments/assets/cfb54615-ac28-4122-8073-4120684b18a8" />

<img width="1252" height="494" alt="image" src="https://github.com/user-attachments/assets/2709d399-f2ff-45f7-921c-1c1dbf24b731" />

<img width="1240" height="495" alt="image" src="https://github.com/user-attachments/assets/eefcc5e3-d4c6-4aaf-889f-8f295e894f7b" />

<img width="1266" height="553" alt="image" src="https://github.com/user-attachments/assets/4d0fec8f-1c7d-48fa-b093-9fdfc3d99b7b" />

<img width="1142" height="513" alt="image" src="https://github.com/user-attachments/assets/cdaad22a-c481-4988-aeee-be3dfa47e3e8" />

<img width="1246" height="482" alt="image" src="https://github.com/user-attachments/assets/08ad1e37-dd6a-486e-b561-aa11c44544fd" />

<img width="715" height="496" alt="image" src="https://github.com/user-attachments/assets/94102bbd-41f9-49b3-a2de-eb04a2939876" />

<img width="1157" height="544" alt="image" src="https://github.com/user-attachments/assets/6f517d71-dc04-4d64-bfc5-27e30cff2717" />

---

## 🧠 Key Learnings
- Built a full-stack MERN application
- Implemented authentication using JWT
- Designed RESTful APIs
- Integrated frontend with backend
- Developed social interaction features

---

## ⚠️ Note
If the project does not run directly due to environment differences, screenshots are provided to demonstrate the functionality.

---

## 👨‍💻 Author
Harshit Verma

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
