# 🔐 FileShareX - FastAPI Secure File Transfer System

**FileShareX** is a secure file-sharing backend built with FastAPI. It enables role-based file operations between two user types: `ops` (uploaders) and `client` (downloaders). The system includes user signup, email confirmation, JWT-based login, role-restricted endpoints, file encryption, and secure download links.

---

## 🚀 Features

- 👤 User signup & login with role selection (`ops` or `client`)
- ✅ Email-based account verification
- 🔐 JWT authentication
- 📤 Secure file uploads (restricted to `.pptx`, `.docx`, `.xlsx`)
- 🔑 Encrypted download links with limited access
- 🧾 Role-based access control
- 🗂️ File metadata listing (for clients only)

---

## 📦 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/filesharex.git
cd filesharex
