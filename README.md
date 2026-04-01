🎓 CampusConnect: A Secure College Social Space
🚀 Overview
CampusConnect is a full-stack social media platform designed specifically for college student communities. Since our institution does not provide student emails, this project implements a unique ID-Card Verification System to ensure a private and safe environment for verified students only.
🛡️ Key Features
Document-Based Verification: Secure upload and admin-approval flow for Student ID cards.
Real-Time Interaction: Instant messaging and live campus feeds using WebSockets.
Security First:
Password Hashing: Argon2/Bcrypt.
Session Security: JWT stored in HttpOnly cookies.
Input Validation: Strict schema validation with Zod to prevent SQL Injection/XSS.
Student Marketplace: A dedicated space for peer-to-peer textbook and gear exchange.
💻 The Tech Stack (2026 Edition)
Frontend: Next.js (React + TypeScript)
Backend: NestJS (Node.js + TypeScript)
Database: PostgreSQL (Relational Data Management)
Real-Time: Socket.io
Storage: AWS S3 (Encrypted storage for ID verification photos)
🏗️ Project Architecture
I am utilizing an Asynchronous, Non-blocking architecture to ensure the UI remains responsive even during heavy data fetches or image uploads.
🛠️ Installation & Setup
(Coming Soon)
Clone the repo: git clone https://github.com
Install dependencies: npm install
Set up .env with your PostgreSQL and AWS credentials.
Run in dev mode: npm run dev
Status: 🚧 Under Active Development
Author: 
