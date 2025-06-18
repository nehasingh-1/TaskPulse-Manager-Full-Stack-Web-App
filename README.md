# TaskPulse Manager - Full Stack Web App

TaskPulse Manager is a full stack task management web application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to register, log in, create tasks, and manage them on a real-time Kanban board interface.

---

## 🔧 Tech Stack

### Frontend (React)
- React.js
- Axios
- React Router
- Socket.io-client

### Backend (Node.js & Express)
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (Authentication)
- Socket.io (Real-time updates)

---

## 📁 Project Structure

```
TaskPulse-Manager/
├── client/                  # Frontend React app
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── App.js
│       ├── index.js
│       ├── api.js
│       ├── components/
│       │   ├── Board.js
│       │   ├── TaskCard.js
│       │   └── Navbar.js
│       └── pages/
│           ├── Login.js
│           ├── Register.js
│           └── Dashboard.js
├── server/                  # Backend Node.js app
│   ├── server.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── models/
│   │   ├── User.js
│   │   └── Task.js
│   └── routes/
│       ├── auth.js
│       └── tasks.js
```

---

## 🚀 Features

- 🔐 User Authentication (JWT-based)
- 🧑‍💼 Register and Login Pages
- 📋 Create, Update, Delete Tasks
- 📊 Kanban-style Task Board UI
- 🔄 Real-time task updates using Socket.IO
- 🔧 Modular backend with Express Routes and Middleware

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/nehasingh-1/TaskPulse-Manager-Full-Stack-Web-App.git
cd TaskPulse-Manager-Full-Stack-Web-App
```

### 2. Install Dependencies

**Frontend**
```bash
cd client
npm install
```

**Backend**
```bash
cd ../server
npm install
```

### 3. Create `.env` file in `server/` folder

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the Application

**Start Backend**
```bash
cd server
npm start
```

**Start Frontend**
```bash
cd client
npm start
```

Visit: `http://localhost:3000`

---


---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

**Neha Singh**  
[GitHub](https://github.com/nehasingh-1)
