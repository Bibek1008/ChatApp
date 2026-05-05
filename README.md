# 💬 ChatApp – Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack and WebSockets, enabling instant messaging with low latency. This project was developed as part of my internship to demonstrate practical implementation of real-time systems and modern web technologies.

---

## 🚀 Features

* ⚡ **Real-time Messaging** using WebSockets (Socket.IO)
* 🔐 **User Authentication** (JWT-based login/signup)
* 🟢 **Online/Offline Status** tracking
* 🖼️ **Image Sharing** via Cloudinary integration
* 👤 **User Profiles** with profile pictures
* 📩 **Message Seen/Delivered Status**
* 📱 **Responsive UI** (mobile-friendly)
* 🔔 **Instant Notifications**

---

## 🛠️ Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB + Mongoose
* Socket.IO
* JWT Authentication
* bcrypt (password hashing)
* Cloudinary (image upload)
* Multer (file handling)

### Frontend

* React (with Vite)
* TypeScript
* Tailwind CSS
* Socket.IO Client
* Axios
* React Router

---

## 📁 Project Structure

```
ChatApp/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── context/
│   └── package.json
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file in backend:

```
PORT=5000
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## 🚀 Getting Started

### 1. Clone the repo

```
git clone https://github.com/Bibek1008/ChatApp.git
cd ChatApp
```

### 2. Install dependencies

```
npm install
npm install --prefix frontend
```

### 3. Run project

```
npm run dev
```

---

## 📡 API Endpoints

### Auth

* POST `/api/auth/signup`
* POST `/api/auth/login`
* POST `/api/auth/logout`

### Messages

* GET `/api/messages/:id`
* POST `/api/messages/send/:id`

### Users

* GET `/api/users`
* PUT `/api/auth/update-profile`

---

## 🎯 Learning Outcomes (Important for Internship)

* Implemented **real-time communication using WebSockets**
* Built scalable **client-server architecture**
* Integrated **Cloudinary for media handling**
* Applied **authentication & security best practices**
* Developed full-stack application using MERN

---

## 🚀 Deployment

* Backend: Render / Railway
* Frontend: Vercel / Netlify

---

## 👨‍💻 Author

**Bibek Bhandari**
CSE Student | MERN Developer

---

## 📌 Note

This project was developed as part of my internship to gain hands-on experience in real-time application development.
