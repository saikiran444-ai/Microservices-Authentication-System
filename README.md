This project provides an authentication system based on microservices, using MongoDB for storage and JWT for authentication. It includes separate services for user registration, login, and password management. Each service runs independently and can be deployed using Docker Compose.

## Features
- User registration, login, and password change services
- MongoDB integration for user data storage
- JWT-based authentication and authorization
- RESTful API-based communication  
- Independent service deployment  
- Docker Compose integration for running all services together  

## Tech Stack
- Node.js  
- Express.js  
- Docker & Docker Compose  
- REST APIs  

## Setup

### Using Docker
```bash
cd Microservices Authentication System/docker-compose
docker-compose up --build
```

### Run Locally (Without Docker)
```bash
cd Microservices Authentication System/Login
npm install
node login-service_server.js
```
Repeat for registration and change password services.

## Example API Endpoints
| Service  | Endpoint  | Method |
|----------|-----------|--------|
| Register | /register | POST   |
| Login    | /login    | POST   |
| Change Password | /change-password | PUT |
