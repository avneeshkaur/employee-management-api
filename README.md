# Employee Management API

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge)

RESTful backend API for employee management with secure JWT authentication.

## ✨ Features
- 🔐 User signup & login with JWT tokens
- 🔒 Password hashing with bcrypt
- 👥 Full CRUD for employee records
- 🏗️ MVC architecture
- 🛡️ Auth middleware for protected routes
- ⚙️ Environment variable support

## 🛠️ Tech Stack
Node.js · Express.js v5 · MongoDB · Mongoose · JWT · bcryptjs · CORS · dotenv

## 🚀 Getting Started
```bash
git clone https://github.com/avneeshkaur/employee-management-api
cd employee-management-api/backend
npm install
# Create .env file:
# MONGO_URI=your_mongodb_uri
# JWT_SECRET=your_secret
# PORT=5000
npm start
```

## 📡 API Endpoints
| Method | Endpoint | Description |
|---|---|---|
| POST | /api/auth/signup | Register new user |
| POST | /api/auth/login | Login, get JWT |
| GET | /api/employees | Get all employees |
| POST | /api/employees | Create employee |
| GET | /api/employees/:id | Get by ID |
| PUT | /api/employees/:id | Update employee |
| DELETE | /api/employees/:id | Delete employee |

## 👩‍💻 Author
**Avneesh Kaur** — [GitHub](https://github.com/avneeshkaur) · [LinkedIn](https://linkedin.com/in/avneeshkaur)