# 🚀 Project Overview

The Secure File Sharing System allows users to upload, encrypt, store, and share files safely.
It ensures confidentiality, integrity, and controlled access using encryption, authentication, OTP verification, and role-based authorization.

This project is designed to demonstrate real-world security practices used in modern web applications.

# ✨ Key Features
## 🔑 Authentication & Authorization

. JWT-based authentication
. Secure login & registration
. Google OAuth 2.0 login
. Role-based access (User / Admin)
. Protected routes (frontend & backend)

# 🔐 File Security
. AES-based file encryption before storage
. Encrypted files stored locally or on AWS S3
. Secure decryption only for authorized users
. Unique encrypted file identifiers

# 📤 File Management
. Upload encrypted files
. Download & decrypt securely
. View uploaded files
. Share files with access control

# 📧 OTP & Sharing
. OTP-based secure file sharing
. Email verification for file access
. Time-bound access tokens

# 🛡️ System Protection
. Rate limiting (API abuse prevention)
. Helmet security headers
. CORS protection
. Input validation
. Error handling middleware

# 👨‍💼 Admin Panel
. View users
. View uploaded files
. Admin-only protected routes
. Scheduled admin reports (cron jobs)
