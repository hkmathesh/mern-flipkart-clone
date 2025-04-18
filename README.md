# 🛒 MERN Flipkart Clone

[![React](https://img.shields.io/badge/Frontend-React-blue.svg?logo=react)](https://reactjs.org/)
[![Backend](https://img.shields.io/badge/Backend-Node.js-green.svg?logo=node.js)](https://nodejs.org/)
[![Database](https://img.shields.io/badge/Database-MongoDB-brightgreen.svg?logo=mongodb)](https://mongodb.com/)
[![Auth](https://img.shields.io/badge/Auth-Firebase-orange.svg?logo=firebase)](https://firebase.google.com/)
[![License](https://img.shields.io/badge/License-Educational-lightgrey)](#license)

> A full-stack e-commerce application inspired by Flipkart, built using the **MERN** stack and **Firebase Authentication**.  
> ✨ For **educational use only** — not affiliated with Flipkart.

---

## 📚 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation & Setup](#-installation--setup)
- [Firebase Config](#-firebase-config)
- [Screenshots](#-screenshots)
- [Live Demo](#-live-demo)
- [Author](#-author)
- [License](#-license)

---

## 🚀 Features

- 🔐 Firebase Auth (Login & Signup)
- 🛍️ Product Browsing with categories
- 🛒 Cart Management (Context API)
- 🧾 Checkout & Order Placement
- 📜 Order History (user-specific)
- 🧩 Protected Routes for auth users
- 💾 MongoDB for products & orders
- 📱 Responsive UI with Tailwind CSS

---

## 🛠️ Tech Stack

### Frontend
- **React** (with [Vite](https://vitejs.dev))
- **React Router**
- **Context API** (Cart Management)
- **Tailwind CSS** (UI Styling)
- **Firebase Auth** (Authentication)

### Backend
- **Node.js** + **Express.js**
- **MongoDB** + **Mongoose**
- **Render** for backend deployment

---

## 📦 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/mern-flipkart-clone.git
cd mern-flipkart-clone

## 🔐 Firebase Config

In your frontend project, create a file at `src/config.js`:

```js
import { initializeApp } from "firebase/app";
import { getAuth } from "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  // ... other config
};

const app = initializeApp(firebaseConfig);
const auth = getAuth(app);
export default auth;

### 🌍 Live Demo
Frontend: https://mern-flipkart-frontend.onrender.com/

Backend API: https://mern-flipkart-backend.onrender.com/

### 🙋‍♂️ Author
Harikrishnan
https://github.com/hkmathesh/mern-flipkart-clone

Passionate MERN stack developer building real-world projects 💻

### 📄 License
This project is licensed for educational and non-commercial use only.
Not affiliated with or endorsed by Flipkart.