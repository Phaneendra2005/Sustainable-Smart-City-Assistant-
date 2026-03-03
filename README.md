# Sustainable Smart City Assistant

A full-stack Smart City Assistant platform designed using a scalable backend architecture and modular frontend integration. The system provides AI-powered city services through secure REST APIs with performance-focused design.

---

## Overview

This platform enables users to interact with smart city services through authenticated API endpoints. The application is structured using layered backend principles to ensure maintainability, scalability, and clean separation of concerns.

The system is designed to support concurrent users with optimized request handling and database performance.

---

## System Architecture

### Backend (Node.js + Express)

The backend follows a layered architecture:

- Controllers – Handle HTTP requests and responses  
- Services – Contain core business logic  
- Middleware – Authentication and request validation  
- Models – Database schema definitions  
- Routes – API endpoint definitions  

This separation ensures modularity and easier scalability.

### Frontend (React.js)

- Component-based UI architecture  
- API-driven data rendering  
- State management using hooks  
- Protected routes for authenticated users  

### Database

- MongoDB for persistent storage  
- Indexed collections to improve query performance  

---

## Authentication & Security

- JWT-based authentication  
- Role-based access control  
- Middleware-level token verification  
- Secure password handling  
- Protected API endpoints  

The backend is stateless, enabling horizontal scalability.

---

## REST API Design

The system follows RESTful principles.

Example endpoints:

- POST /auth/register  
- POST /auth/login  
- GET /api/services  
- POST /api/request  
- GET /api/history  

Each endpoint is validated, modular, and secured using middleware.

---

## Technology Stack

### Backend
- Node.js
- Express.js
- JWT Authentication
- MongoDB

### Frontend
- React.js
- REST API integration

### Tools & Deployment
- Git
- AWS (if deployed)
- Environment-based configuration

---

## Performance & Scalability Considerations

- Modular service separation for maintainability  
- Optimized database queries  
- Stateless backend architecture  
- Efficient handling of concurrent requests  
- Achieved sub-3 second response time under testing  

---

## Engineering Highlights

- Clean separation of concerns  
- Reusable middleware components  
- API-first backend design  
- Secure authentication workflow  
- Scalable structure suitable for future microservices migration  

---

## Local Setup Instructions

### Clone Repository

git clone <repository-url>  
cd Sustainable-Smart-City-Assistant  

### Backend Setup

cd backend  
npm install  
npm start  

### Frontend Setup

cd frontend  
npm install  
npm start  

Create a .env file in backend directory:

MONGO_URI=your_database_connection  
JWT_SECRET=your_secret_key  

---

## Future Improvements

- Containerization using Docker  
- CI/CD pipeline integration  
- API rate limiting  
- Caching layer (Redis)  
- Migration toward microservices architecture  

---

## Author

Phaneendra Kanduri  
B.Tech Computer Science and Engineering  
Backend & Platform Engineering Enthusiast  
