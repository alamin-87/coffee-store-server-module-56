# ☕ Coffee Store – Backend (Server)

This is the **backend API** for the Coffee Store MERN project. Built using **Node.js**, **Express.js**, and **MongoDB**, it provides a secure, RESTful interface for managing coffee products including **Create, Read, Update, Delete (CRUD)** operations.

---

## 🌐 Live API Server

🔗 [Deployed API Endpoint](https://coffee-store-server.onrender.com/) <!-- Replace with your actual backend deployment URL -->

---

## ⚙️ Tech Stack

- **Runtime**: Node.js
- **Web Framework**: Express.js
- **Database**: MongoDB (Cloud – MongoDB Atlas)
- **Environment Config**: dotenv
- **CORS & JSON Parsing**: Express Middleware
- **API Testing Tool**: Postman

---

## ✨ API Features

- 📥 **POST** `/coffee` – Add a new coffee item  
- 📄 **GET** `/coffee` – Retrieve all coffee items  
- 🔍 **GET** `/coffee/:id` – Get single coffee by ID  
- ✏️ **PUT** `/coffee/:id` – Update coffee details  
- ❌ **DELETE** `/coffee/:id` – Delete coffee by ID

All requests are JSON-based and support proper status codes.

---

## 📁 Folder Structure
coffee-store-server/
├── node_modules/
├── .env
├── index.js
├── package.json
└── README.md

---

## 📦 Dependencies

```json
{
"express": "^4.18.2",
"mongodb": "^5.7.0",
"cors": "^2.8.5",
"dotenv": "^16.4.5",
"nodemon": "^3.0.3"
}
```
---

## 📁 Clone the Repository
git clone https://github.com/yourusername/coffee-store-server.git
cd coffee-store-server

