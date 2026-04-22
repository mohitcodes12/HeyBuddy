# 👋 HeyBuddy

A full-stack real-time chat application where users can create and join
rooms, send instant messages, and see who's online — built with 
WebSockets, Node.js, and MongoDB.

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Tech](https://img.shields.io/badge/Stack-MERN%20%2B%20Socket.io-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Live Demo
> Coming soon — deployment in progress

---

## ✨ Features

- 🔐 User authentication with JWT (Register / Login)
- 🏠 Create and join multiple chat rooms
- ⚡ Real-time messaging with sub-100ms delivery
- 🟢 Live online / offline user presence
- 💾 Persistent message history stored in MongoDB
- 📱 Fully responsive UI

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| React | UI framework |
| Tailwind CSS | Styling |
| Socket.io Client | Real-time communication |

### Backend
| Technology | Purpose |
|---|---|
| Node.js + Express | REST API server |
| Socket.io | WebSocket server |
| MongoDB + Mongoose | Database |
| Redis | Online presence tracking |
| JWT + bcrypt | Authentication & security |

---

## 📁 Project Structure
heybuddy/
│
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chat/        # Chat window, messages
│   │   │   ├── Room/        # Room list, create room
│   │   │   └── Auth/        # Login, Register
│   │   ├── socket/          # Socket.io client setup
│   │   └── App.jsx
│
├── server/                  # Node.js backend
│   ├── config/              # DB connection
│   ├── models/              # User, Room, Message schemas
│   ├── routes/              # Auth, Room API routes
│   ├── controllers/         # Business logic
│   ├── middleware/          # JWT verification
│   └── socket/              # Socket event handlers

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- Redis (local or cloud)

### Installation

```bash
# Clone the repo
git clone https://github.com/mohitcodes12/heybuddy.git
cd heybuddy

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file inside `/server`:

```env
PORT=3001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
REDIS_URL=your_redis_url
```

### Run the App

```bash
# Start server (from /server)
npm run dev

# Start client (from /client)
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🗺️ Development Roadmap

- [x] Project setup and folder structure
- [ ] User authentication (Register/Login with JWT)
- [ ] REST API for rooms and messages
- [ ] WebSocket integration with Socket.io
- [ ] Real-time messaging with room support
- [ ] Online presence with Redis
- [ ] Frontend UI with React + Tailwind
- [ ] Deployment (Railway + Vercel)

---

## 📸 Screenshots
> Coming soon

---

## 🤝 Connect

**Mohit Kumar Verma**
- GitHub: [@mohitcodes12](https://github.com/mohitcodes12)
- LinkedIn: [mohit-kumar-verma](https://www.linkedin.com/in/mohit-kumar-verma-b45586267/)
- Email: mohit.kverma12@gmail.com

---

> ⭐ Star this repo if you find it interesting!
