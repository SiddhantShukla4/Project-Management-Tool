# 📁 Project Management Tool

A full-stack Project Management Tool designed to streamline planning, tracking, and collaboration for your team. This tool helps users manage projects, assign tasks, track progress, and improve team productivity.

---

## 🚀 Features

- User authentication (register/login)
- Create and manage projects
- Add, assign, and update tasks
- Role-based access control
- Real-time updates (optional with WebSockets)
- Responsive frontend built with React
- Backend REST API using Node.js and Express
- MongoDB for data storage

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT for authentication

---

## 📦 Installation & Setup

### 1. Add this to your .env file in backend folder

```env
MONGO_URI=your_mongo_uri
JWT_SECRET=secret or anything random
CLIENT_URL=http://localhost:3000
PORT=8000
```
### 2. Clone the repository

```bash
git clone https://github.com/your-username/project-management-tool.git
cd project-management-tool
```
### 3. Backend Setup 
```bash
cd backend
npm install
npm run dev
```

### 4. Frontend Setup
```bash
cd ../client
npm install
npm start
```


