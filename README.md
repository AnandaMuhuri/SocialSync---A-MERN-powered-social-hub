# SocialSync---A-MERN-powered-social-hub# SocialSync - A MERN-Powered Social Hub

## 🚀 Overview
SocialSync is a **full-stack social media application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It allows users to **register, log in, create posts, like posts, and engage with other users** in an interactive environment.

## 🎯 Features
- **User Authentication** – Secure sign-up and login with **JWT authentication**.
- **Post Creation & Interaction** – Users can create, like, and comment on posts.
- **Profile Management** – Users can update their profiles and manage their content.
- **Responsive UI** – Optimized for all devices using **Material-UI**.
- **Image Uploads** – Uses **Multer & Cloudinary** for handling image uploads.
- **State Management** – **Redux Toolkit** for efficient global state handling.

## 🛠️ Tech Stack
### **Frontend**
- React.js
- Redux Toolkit
- Material-UI
- React Router

### **Backend**
- Node.js
- Express.js
- MongoDB & Mongoose
- Multer (for image uploads)
- Bcrypt (password hashing)
- JSON Web Tokens (JWT) for authentication
- Cloudinary (image hosting)
- Dotenv (environment variable management)

## 🚀 Getting Started
### **1. Clone the Repository**
```bash
git clone https://github.com/AnandaMuhuri/SocialSync---A-MERN-powered-social-hub.git
cd SocialSync---A-MERN-powered-social-hub
```

### **2. Install Dependencies**
#### **Frontend**
```bash
cd client
npm install
```
#### **Backend**
```bash
cd server
npm install
```

### **3. Set Up Environment Variables**
Create a `.env` file inside the `server` folder and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### **4. Run the Application**
#### **Start Backend**
```bash
cd server
npm start
```
#### **Start Frontend**
```bash
cd client
npm start
```

The application will run on **http://localhost:3000** (frontend) and **http://localhost:5000** (backend).

## 🎯 Contributing
Feel free to **fork this repository, submit issues, or create pull requests** to improve this project!

## 📄 License
This project is licensed under the **MIT License**.

---
🚀 **SocialSync - Connect, Share, and Engage!**

