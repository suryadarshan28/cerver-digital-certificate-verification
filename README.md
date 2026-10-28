# Cerver – Digital Certificate Verification System

Cerver is a full-stack web application for managing and verifying digital certificates online.

## Features

- Admin and normal-user authentication
- Password hashing and JWT-based authentication
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
- `backend/` – Express API, routes, models, and authentication

## Local Setup

### Backend

```bash
cd backend
npm install
```

Configure the required environment variables in `backend/.env`, then start the server:

```bash
npm start
```

### Frontend

Open a second terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in the frontend terminal.

## Security

Never upload `.env` files, database credentials, or JWT secrets to GitHub.
