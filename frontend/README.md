# Cerver – Digital Certificate Verification System

Cerver is a full-stack web application that allows users to verify digital certificates securely.

## Features
- Admin and normal-user authentication
- Secure password hashing and JWT-based authentication
- Role-based access control
- Certificate creation and management
- Public certificate verification
- QR code generation and PDF certificate support
- MongoDB database integration

## Technology Stack
- Frontend: React, Vite, Bootstrap
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT and bcrypt

## Project Structure
- `frontend/` – React frontend
- `backend/` – Express backend and API routes

## Local Setup

### 1. Install backend dependencies
```bash
cd backend
npm install
```

### 2. Configure environment variables
Create a `.env` file inside `backend/` using the variables described in `backend/.env.example`, if that file exists. Use your own MongoDB connection string and JWT secret.

### 3. Start the backend
```bash
npm start
```

### 4. Install and start the frontend
Open a second terminal:
```bash
cd frontend
npm install
npm run dev
```

Open the local URL shown in the frontend terminal.

## Security
Do not commit `.env` files, passwords, database credentials, or JWT secrets.
