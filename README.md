
# 💬 Fullstack Real-Time Chat App

A real-time chat application built with the **MERN stack**, featuring **Socket.io** for real-time messaging, **Zustand** for state management, and a beautifully styled UI with **TailwindCSS** and **DaisyUI**.

---

## 🚀 Highlights

- 🌟 **Tech Stack**: MongoDB, Express.js, React, Node.js (MERN), Socket.io
- 🎃 **Authentication & Authorization**: Secured with JWT tokens
- 👾 **Real-time Messaging**: Instant communication using Socket.io
- 🚦 **Online User Status Tracking**
- 📦 **Global State Management**: Zustand
- 🐞 **Robust Error Handling**: Both server-side and client-side
- 🎨 **UI/UX**: TailwindCSS and DaisyUI for modern design
- ⚡ **Free Deployment Ready**
- ⏳ **And more features planned**

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dev-rajankit/fullstack-chat-app.git
cd fullstack-chat-app
````

### 2️⃣ Setup Backend

```bash
cd backend
npm install
# Add your .env configuration (MongoDB URI, JWT secret, Cloudinary keys)
npm run dev
```

### 3️⃣ Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

* Frontend runs on: **[http://localhost:5173](http://localhost:5173)**
* Backend runs on: **[http://localhost:5001](http://localhost:5001)**

---

## 🌐 Environment Variables

Create a `.env` file inside **/backend** with:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

---

## 🙌 Acknowledgements

This project is inspired by the YouTube tutorial by **[Burak Orkmez](https://github.com/burakorkmez/fullstack-chat-app)**.
I built and customized this app as part of my **MERN stack learning journey**, adding my own understanding, experiments, and features.

---

## 👨‍💻 About Me

Made with 💙 by **Ankit Raj**

* GitHub: [dev-rajankit](https://github.com/dev-rajankit)