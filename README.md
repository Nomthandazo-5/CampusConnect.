# CampusConnect.
A student messaging platform built with Node.js, Express, MongoDB, and JWT authentication.

 🚀 Features
- User registration and login (JWT auth)
- Send/receive messages between users
- Protected routes with authentication

💻 Tech Stack
- Backend: Node.js, Express
- DB: MongoDB (mongoose)
- Auth: JWT

 📥 Setup
1. Clone repo
2. cp .env.example .env
3. Set MONGO_URI and JWT_SECRET in .env
4. npm install
5. Run npm run dev to start in dev mode

 🧪 API Endpoints
- POST /api/auth/register – { name, email, password }
- POST /api/auth/login – { email, password }
- POST /api/messages/send – { to, text }, *auth token needed*
- GET /api/messages/ – Get all messages for logged-in user

🧼 Improvements
- Add chat UI with React/Android
- Real-time chat with Socket.io
- Password reset flow

