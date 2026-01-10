# 🚀 Project Overview

The Secure File Sharing System allows users to upload, encrypt, store, and share files safely.  
It ensures confidentiality, integrity, and controlled access using encryption, authentication, OTP verification, and role-based authorization.

This project demonstrates real-world security practices used in modern web applications.

---

# ✨ Key Features

## 🔑 Authentication & Authorization
- JWT-based authentication
- Secure login and registration
- Google OAuth 2.0 login
- Role-based access control (User / Admin)
- Protected routes (frontend and backend)

## 🔐 File Security
- AES-based file encryption before storage
- Encrypted files stored locally or on AWS S3
- Secure decryption only for authorized users
- Unique encrypted file identifiers

## 📤 File Management
- Upload encrypted files
- Download and decrypt files securely
- View uploaded files
- Share files with controlled access

## 📧 OTP & Secure Sharing
- OTP-based secure file sharing
- Email verification for file access
- Time-bound access tokens

## 🛡️ System Protection
- Rate limiting to prevent API abuse
- Helmet security headers
- CORS protection
- Input validation
- Centralized error handling middleware

## 👨‍💼 Admin Panel
- View registered users
- View uploaded files
- Admin-only protected routes
- Scheduled admin reports using cron jobs

## 🧱 Tech Stack

### 🌐 Frontend
- React.js
- React Router
- Axios
- Tailwind CSS

### 🖥️ Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- Passport.js (Google OAuth 2.0)
- JWT-based authentication

### 🔒 Security & Utilities
- AES encryption
- bcrypt for password hashing
- Multer for secure file handling
- Nodemailer for email services
- Rate limiting for API protection
- Helmet for HTTP security headers
- Cron jobs for scheduled tasks

## 🧱 Tech Stack

### 🌐 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react" height="28"/> React.js &nbsp;
  <img src="https://skillicons.dev/icons?i=tailwind" height="28"/> Tailwind CSS &nbsp;
  <img src="https://skillicons.dev/icons?i=js" height="28"/> JavaScript &nbsp;
</p>

### 🖥️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs" height="28"/> Node.js &nbsp;
  <img src="https://skillicons.dev/icons?i=express" height="28"/> Express.js &nbsp;
  <img src="https://skillicons.dev/icons?i=mongodb" height="28"/> MongoDB &nbsp;
</p>

### 🔒 Security & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=aws" height="28"/> AWS &nbsp;
  <img src="https://skillicons.dev/icons?i=docker" height="28"/> Docker &nbsp;
  <img src="https://skillicons.dev/icons?i=git" height="28"/> Git &nbsp;
</p>

## 🏗️ System Architecture — Encrypted File Share

## 🏗️ System Architecture — Encrypted File Share

```
# ===========================
# CLIENT LAYER (Frontend)
# ===========================
┌─────────────────────────┐
│        Client (UI)       │
│  React + Tailwind CSS    │
│  Browser / Mobile        │
└─────────────┬───────────┘
              │ HTTPS + JWT
              ▼

# ===========================
# API SERVER LAYER (Backend)
# ===========================
┌─────────────────────────┐
│   API Gateway / Server  │
│   Node.js + Express.js  │
│                         │
│ ┌─────────────────────┐ │
│ │ Authentication Layer│
│ │ JWT / Google OAuth  │
│ └─────────────────────┘ │
│                         │
│ ┌─────────────────────┐ │
│ │ Authorization Layer │
│ │ RBAC (User/Admin)   │
│ └─────────────────────┘ │
│                         │
│ ┌─────────────────────┐ │
│ │ Encryption Engine   │
│ │ AES (File Encrypt) │
│ └─────────────────────┘ │
│                         │
│ ┌─────────────────────┐ │
│ │ File Services       │
│ │ Upload / Download  │
│ │ Share / OTP        │
│ └─────────────────────┘ │
│                         │
│ ┌─────────────────────┐ │
│ │ Security Middleware │
│ │ Helmet / RateLimit  │
│ └─────────────────────┘ │
└─────────────┬───────────┘
              │
              ▼

# ===========================
# STORAGE LAYER
# ===========================
┌─────────────────────────┐
│        Storage Layer    │
│ ┌─────────────────────┐│
│ │ MongoDB (Metadata)  ││
│ └─────────────────────┘│
│ ┌─────────────────────┐│
│ │ Local Storage / S3  ││
│ │ Encrypted Files     ││
│ └─────────────────────┘│
└─────────────────────────┘
```



