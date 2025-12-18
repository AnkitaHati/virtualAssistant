# 🤖 AI Virtual Assistant — JARVIS-Style MERN Application

AI Virtual Assistant is a full-stack MERN application that brings a **voice-enabled, intelligent assistant** to life.
Inspired by JARVIS, this assistant can **listen, think, speak, and remember users**, powered by **Gemini AI**, **Web Speech API**, and a secure backend.

The project demonstrates real-world AI integration, authentication, cloud storage, and full deployment.

---

## 🚀 Live Demo

| Component | Link |
|------------|------|
|🧠 **Backend (API Server)** | [https://virtualassistant-backend-4zux.onrender.com](https://virtualassistant-backend-4zux.onrender.com)|
|💻 **Frontend (Web App)** | [https://virtualassistant-7wme.onrender.com](https://virtualassistant-7wme.onrender.com)|

---

## 🧩 Features

### 🎙️ Voice-Enabled Assistant
- Real-time voice input using Web Speech API
- Natural voice responses (Text-to-Speech)
- Optimized speech recognition for better accuracy

### 🧠 AI Intelligence
- Smart conversational replies powered by **Gemini AI**
- Context-aware responses
- Customizable assistant behavior

### 👤 Authentication & Personalization
- Secure Login / Signup using JWT & bcryptjs
- Persistent user sessions
- Customize assistant name
- Upload custom assistant avatar image

### 🎨 UI & Experience
- Fully responsive design
- Smooth UI interactions
- GIF + text-based assistant responses
- Mobile-friendly experience

---

⚙️ Backend (Node.js + Express)
- RESTful API architecture
- MongoDB Atlas cloud database
- JWT-based authentication
- Password hashing with bcryptjs
- Cloudinary integration for image uploads
- Multer for handling file uploads
- Secure environment-based configuration

---

## 🛠️ Tech Stack

|Layer | Technologies|
|-------|---------------|
| **Frontend** | React, Web Speech API, Axios|
| **Backend** | Node.js, Express.js|
| **Database** | MongoDB Atlas|
| **AI Engine** | Gemini AI|
| **Authentication** | JWT, bcryptjs|
| **Cloud & Storage** | Cloudinary, Multer|
| **Deployment** | Render (Backend), Vercel (Frontend)|

---

## 🔒 Environment Variables (Sample)

⚠️ Never commit real secrets to GitHub.

```env
# Backend (`backend/.env`)

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret

Frontend (client/.env)

VITE_BACKEND_URL=https://virtualassistant-backend-4zux.onrender.com

```

## 🏗️ Project Structure

```env
AI-Virtual-Assistant/
│
├── backend/           # Node.js + Express API
│   ├── controllers/   # Business logic
│   ├── models/        # MongoDB schemas
│   ├── routes/        # API routes
│   ├── middleware/    # Auth & validation
│   └── index.js
│
├── client/            # React frontend
│   ├── src/
│   └── public/
│
└── README.md

```

## 🚀 Deployment Overview

- Backend deployed on Render with environment-based configuration
- Frontend deployed on Vercel
- MongoDB Atlas used for cloud database
- CORS enabled for seamless frontend-backend communication
- Production-ready deployment pipeline

---

## 🎯 Learning Outcomes

- Full MERN stack architecture
- AI integration using Gemini
- Voice-based web applications
- Secure authentication systems
- File uploads & cloud storage
- Production deployment & environment handling
- Real-world project structuring

---

## 👩‍💻 Author

**Ankita Hati**  
B.Tech Computer Science & Engineering | KIIT University  
📍 Kolkata, India  

🌐 [GitHub](https://github.com/AnkitaHati)  
🔗 [LinkedIn](https://www.linkedin.com/in/ankita-hati)

---

## 🌱 Future Enhancements

- Multi-language voice support
- AI memory & conversation history
- Wake-word activation (Hey JARVIS)
- Mobile app version
- Emotion-based voice responses

---

## 🙌 Acknowledgement

This project was built as a full-stack AI learning initiative, showcasing how modern AI, voice technologies, and the MERN stack can be combined to create intelligent, real-time virtual assistants.

---