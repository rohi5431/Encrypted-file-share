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
