# 🔧 Node REST API Starter

A production-ready starter template for building RESTful APIs with Node.js and Express. Comes with authentication, organized routing, error handling, and best practices baked in.

## 🛠️ Built With

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- 🔐 JWT authentication (login / register)
- 🗂️ Modular route structure
- ✅ Input validation with express-validator
- 🔒 Helmet.js for security headers
- 🌍 CORS configured
- 📋 Request logging with Morgan
- ❌ Centralized error handling
- 📁 Clean MVC folder structure

## 📁 Project Structure

```
node-rest-api-starter/
├── src/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── app.js
├── .env.example
├── package.json
└── README.md
```

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/darkunde/node-rest-api-starter.git
cd node-rest-api-starter

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Start the server
npm run dev
```

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | Login and get JWT token |
| GET | /api/users/me | Get current user (protected) |

## 📄 License

MIT License

---

Made with ❤️ by [Rushikesh Darkunde](https://github.com/darkunde)
