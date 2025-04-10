# E-Gram-Panchayat---Fullstack-Web-App

A full-featured web application to manage services and user roles (User, Staff, Admin) for Gram Panchayat services.

---

## 🔗 Tech Stack

### 🔧 Backend
- Node.js
- Express.js
- Firebase Admin SDK
- JWT & Middleware Auth
- CORS, Axios

### 🎨 Frontend
- React.js
- Bootstrap
- React Router DOM
- Firebase Authentication

---

## 🚀 Features

- 🔐 Role-based Authentication (Admin / Staff / User)
- 📩 Firebase-based registration & login
- 🛠️ Create/Update/Delete Panchayat services
- 🧑 Dashboards for each user role
- 🌐 Protected Routes
- 📡 Firebase token validation via Express

---

## 📁 Project Structure

```bash
e-gram/
├── backend/
│   ├── server.js
│   ├── firebaseAdmin.js
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── .env
├── frontend/
│   ├── src/
│   ├── public/
│   └── .env
