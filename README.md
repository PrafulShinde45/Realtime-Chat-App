# ✨ Full Stack Realtime Chat App ✨

A modern, real-time messaging application built with the **MERN stack**, featuring **Socket.IO** for instant communication, beautiful UI with **Tailwind CSS + DaisyUI**, image upload with **Cloudinary**, and state management using **Zustand**. This app is fully deployed for free and optimized for real-world scalability, performance, and developer experience.

---

## 🌐 Live Demo

🚀 [Click to Try the Live Chat App](https://realtime-chat-app-iq1x.onrender.com/login)  
🔗 Hosted using: **Render (Fullstack: Backend + Frontend)**  
🖥️ Best viewed on: Desktop & Mobile (responsive)

---

## 🔥 Key Features

- 🌟 **Tech Stack**: MongoDB, Express.js, React.js, Node.js
- 🎃 **Authentication & Authorization**: JWT-based secure login/signup with protected routes
- 👾 **Real-time Chat**: Powered by Socket.IO for instant message delivery
- 🚀 **Online User Status**: Live updates when users come online or go offline
- 🧠 **Zustand**: For global, efficient state management on the frontend
- 🖼️ **Image Upload Support**: Integrated with Cloudinary
- 🧪 **Robust Error Handling**: On both frontend and backend sides
- 📦 **Fully Responsive UI**: Mobile-first and responsive across all screens

---

## 🧠 Technologies Used

| Layer         | Technologies |
|---------------|--------------|
| Frontend      | React.js, TailwindCSS, DaisyUI, Zustand, Axios, Socket.IO-client |
| Backend       | Node.js, Express.js, Socket.IO, JWT, Bcrypt.js, MongoDB |
| Cloud Storage | Cloudinary |
| Deployment    | Render (Fullstack App), MongoDB Atlas (Database) |

---

## ⚙️ Environment Variables Setup

Create a `.env` file in the backend root:

```env
MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

### Build the app
npm run build

### Start the app
npm start

