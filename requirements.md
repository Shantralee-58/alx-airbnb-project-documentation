# 📌 Airbnb Clone – Backend Requirements Specification

This document outlines the **functional** and **technical** requirements for key features of the Airbnb Clone backend. These specifications guide the development of robust, scalable, and secure backend services.

---

## 1. 🔐 User Authentication

### ✅ Functional Requirements
- Allow users to register as **guest** or **host**
- Enable login via **email and password**
- Generate a **JWT token** upon successful authentication
- Enable secure access to protected endpoints
- Implement **role-based access control**

### 🔧 API Endpoints

| Method | Endpoint          | Description                    |
|--------|-------------------|--------------------------------|
| POST   | `/api/register`   | Register a new user            |
| POST   | `/api/login`      | Authenticate user & return JWT |
| GET    | `/api/profile`    | Retrieve logged-in user info   |

### 🔄 Input/Output

#### `/api/register`
```json
Input:
{
  "full_name": "Idah Khumalo",
  "email": "idah@example.com",
  "password": "StrongPassword123!",
  "role": "host"
}

Success Output:
{
  "message": "User registered successfully",
  "user": {
    "id": 1,
    "email": "idah@example.com",
    "role": "host"
  },
  "token": "JWT_TOKEN"
}

