
# Real Time Chat App 

# Project Link: https://chat-app-sepia-eight-75.vercel.app/

A real-time chat application built with **React (frontend)** and **Node.js + Express + Socket.IO (backend)**.
It allows users to connect, send and receive messages instantly in a smooth and responsive UI.

---

##  Features

* Real-time messaging with **Socket.IO**
* User authentication (login/signup)
* Online/offline status indicators
* Responsive design with modern UI
* Backend API for managing users & chats

---

##  Tech Stack

**Frontend**

* React.js
* TailwindCSS (for styling)

**Backend**

* Node.js
* Express.js
* Socket.IO
* MongoDB (for storing users, chats, and messages)

---

##  Project Structure

```
chat-app/
│── client/            # Frontend (React)
│   ├── src/
│   ├── public/
│   └── package.json
│
│── server/            # Backend (Node.js + Express + Socket.IO)
│   ├── models/        # MongoDB schemas
│   ├── routes/        # API routes
│   ├── socket/        # Socket.IO events
│   ├── server.js      # Entry point
│   └── package.json
│
└── README.md
```

---

##  Installation & Setup

### 1 Clone the repository

```bash
git clone https://github.com/yashj-010/Chat-app.git
cd chat-app
```

### 2 Install dependencies

For **backend**:

```bash
cd server
npm install
```

For **frontend**:

```bash
cd client
npm install
```

### 3 Environment Variables

Create a `.env` file inside `server/` and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4 Run the app

Run backend:

```bash
cd server
npm start
```

Run frontend:

```bash
cd client
npm start
```

---

##  Deployment

* **Frontend**: Vercel
* **Backend**: Vercel

---

## 📸 Screenshots

<img width="2879" height="1724" alt="image" src="https://github.com/user-attachments/assets/f52b4a0b-5567-4310-8d79-e063fd12fbf3" />
<img width="2879" height="1722" alt="image" src="https://github.com/user-attachments/assets/01248ffb-66ed-41d1-b23c-f8369ace4323" />

---


# Author
## Yash Jain
