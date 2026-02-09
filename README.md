<h1 align="center">📚 BookWorm – Full‑Stack React Native App 🚀</h1>
📚 BookWorm
Full-Stack React Native Application

A production-grade full-stack mobile application built with React Native, Expo, Node.js, Express, and MongoDB.
Designed to work seamlessly on real Android/iOS devices, emulators, and web, with a focus on scalability, clean architecture, and real-world patterns.

🎯 Project Overview

This project goes beyond UI and covers the entire application lifecycle:

End-to-end authentication

RESTful backend API

Media uploads & cloud storage

Pagination & performance optimization

Mobile + web compatibility

Environment-based configuration

No native Android/iOS code
No paid services required
Fully deployable & production-ready

🚀 Key Features
🔐 Authentication

Secure Signup & Login

JWT-based stateless authentication

Centralized error handling for invalid credentials

🏠 Home Feed

Newest-first post ordering

Infinite scrolling using cursor-based pagination

Optimized API responses for performance

➕ Post Management

Create posts with:

Title

Rating

Caption

Cover image (required)

Image upload via Cloudinary

👤 User Profile

Displays user information

Lists all posts created by the user

🗑️ Post Deletion

Safe delete with confirmation alert

Authorization checks (only owner can delete)

🎨 Theming

4 pre-configured themes

Theme switch by changing a single color object

🌐 Cross-Platform Support

Runs on:

Android

iOS

Web (localhost)

Same codebase for all platforms

🚪 Logout

Secure token removal

Clean session termination

🧠 Technical Learnings & Concepts

Building REST APIs with Node.js & Express

MongoDB schema design and relationships

Stateless authentication using JWT

Cursor-based pagination for infinite scrolling

Handling image uploads (Base64 → Cloudinary)

Environment-based configuration using .env

Cross-platform navigation with Expo Router

Debugging on real devices without Android Studio/Xcode

Free backend deployment (Render / Railway)

🧩 Tech Stack
Frontend

React Native

Expo

Expo Router

JavaScript

Backend

Node.js

Express.js

MongoDB

JWT Authentication

Cloudinary (media storage)

📁 Environment Variables Setup
Backend (/backend/.env)
PORT=3000
MONGO_URI=<YOUR_MONGODB_CONNECTION_STRING>
JWT_SECRET=<YOUR_SECURE_JWT_SECRET>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

API_URL=<YOUR_DEPLOYED_BACKEND_URL>


⚠️ .env files are intentionally excluded from version control.

⚙️ Running the Backend
cd backend
npm install
npm run dev


Backend will start on:

http://localhost:3000

📱 Running the Mobile App
cd mobile
npm install
npx expo start


Scan QR code using Expo Go

Or run on emulator / browser

🔐 Security Notes

.env files are ignored via .gitignore

Sensitive credentials are never committed

Public Expo variables use EXPO_PUBLIC_* prefix
