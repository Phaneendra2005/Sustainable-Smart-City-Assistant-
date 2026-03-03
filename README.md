# Sustainable Smart City Assistant

A full-stack AI-powered Smart City Assistant platform designed to provide intelligent city services through a scalable backend architecture and modular frontend integration.

---

## 🚀 Overview

The system enables users to interact with smart city services such as sustainability recommendations, AI-driven assistance, and real-time information access through secure REST APIs.

The platform is built using a layered backend architecture with authentication, modular services, and optimized database interactions.

---

## 🏗️ Architecture

The system follows a structured layered architecture:

Backend (Node.js + Express):
- Controllers → Handle HTTP requests and responses
- Services → Business logic layer
- Middleware → Authentication & request validation
- Models → Database schema definitions
- Routes → API endpoint definitions

Frontend (React.js):
- Component-based UI architecture
- API-driven data rendering
- State management using hooks
- Protected routes for authenticated access

Database:
- MongoDB for persistent storage
- Indexed collections for optimized query performance

---

## 🔐 Authentication & Security

- JWT-based authentication
- Role-based access control
- Middleware-level token validation
- Secure password handling
- Protected API endpoints

---

## 📡 API Design

RESTful API principles followed:

- `POST /auth/register`
- `POST /auth/login`
- `GET /api/services`
- `POST /api/request`
- `GET /api/history`

Each endpoint is modular, validated, and secured via middleware.

---

## ⚙️ Tech Stack

Backend:
- Node.js
- Express.js
- JWT Authentication
- MongoDB

Frontend:
- React.js
- REST API integration

Tools & Deployment:
- Git
- AWS (if deployed)
- Environment-based configuration

---

## 📈 Performance Considerations

- Modular service separation for maintainability
- Optimized database queries
- Stateless backend architecture
- Efficient request handling under concurrent load
- Reduced response time to sub-3 seconds during testing

---

## 🧠 Engineering Highlights

- Clean separation of concerns
- Reusable middleware components
- API-first backend design
- Secure authentication workflow
- Scalable architecture suitable for extension

---

## 🛠️ Local Setup

### Backend

```bash
git clone <repo-url>
cd backend
npm install
npm start
