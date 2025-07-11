# 💬 QuickChat - Chat with Love

**QuickChat** is a real-time messaging application that lets users connect, chat, and share images instantly. Built with **React.js**, **Node.js**, and **Socket.IO**, it provides a smooth and modern chat experience with live status updates and media sharing.

---

## 🚀 Features

- 🔐 **User Authentication**
    - Secure signup/login with JWT (JSON Web Tokens)
    - Passwords hashed with bcrypt
    - Token stored in localStorage

- 💬 **Realtime Chat**
    - Instant messaging with **Socket.IO**
    - Text and image messages
    - Seamless and fast delivery

- ✅ **Live Status**
    - Online/offline indicator for users
    - Realtime status updates
    - Unseen message count

- 📁 **Image Upload via Cloudinary**
    - All images shared in chats are uploaded to **Cloudinary**
    - Fast and reliable image delivery
    - Temporary image preview before upload

- 🖼️ **Media Gallery**
    - Scrollable image history with each user
    - Click-to-view full image

- 🧑‍💻 **Profile Features**
    - Editable bio and profile picture
    - View other user details

---

## 🛠 Tech Stack

### Frontend
- **React.js**
- **Axios** – for API requests
- **react-router-dom** – for routing
- **Tailwind CSS** – for responsive UI
- **react-hot-toast** – for toast notifications

### Backend
- **Node.js** + **Express.js**
- **Socket.IO** – for realtime messaging
- **JSON Web Token (JWT)** – for authentication
- **bcrypt.js** – for password hashing

### Image Storage
- **Cloudinary**
    - Used to store and retrieve image files securely.
    - Images are uploaded directly from the frontend before being sent as messages.

---

## 📦 Installation

1. **Clone the repository**
     ```bash
     git clone https://github.com/yourusername/quickchat-app.git
     cd quickchat-app
     ```

2. **Install dependencies**

     **Frontend**
     ```bash
     cd frontend
     npm install
     ```

     **Backend**
     ```bash
     cd ../backend
     npm install
     ```

3. **Environment Variables**

     Create `.env` files for both frontend and backend:

     **.env (Backend)**
     ```ini
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     ```

     **.env (Frontend - Vite/React)**
     ```ini
     VITE_BACKEND_URL=http://localhost:5000
     ```

4. **Run the App**

     **Start backend**
     ```bash
     cd backend
     npm run dev
     ```

     **Start frontend**
     ```bash
     cd ../frontend
     npm run dev
     ```

---

## 📸 Screenshots

_Add UI screenshots here (chat window, login/signup page, image preview, etc.)_

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!  
Feel free to check the issues page.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Cloudinary
- Socket.IO
- React
- Tailwind CSS

---

Let me know if you want:
- Custom badges (Live site, License, Tech)
- Deployment section (Vercel/Render/Netlify)
- Demo video or animated preview

Just ask and I’ll add it for you!