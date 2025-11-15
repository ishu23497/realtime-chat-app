🗨️ Realtime Chat App

A full-stack real-time chat application built using React, Node.js, Express, MongoDB, and Socket.io.

🚀 Features

🔐 User Authentication (JWT + bcrypt)

💬 Real-Time Messaging (Socket.io)

👤 Online User Status

📩 One-to-One Private Chats

🗄️ MongoDB Database

⚡ Production Ready API

📁 Folder Structure
realtime-chat-app/
│
├── backend/       
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── config
│   ├── server.js
│   └── package.json
│
└── frontend/      
    ├── src
    ├── public
    └── package.json

🛠️ Tech Stack
Frontend

React.js

Context API

Axios

CSS

Backend

Node.js

Express.js

MongoDB (Mongoose)

Socket.io

JsonWebToken

🔧 Installation
Clone repository
git clone https://github.com/ishu23497/realtime-chat-app.git
cd realtime-chat-app

▶️ Backend Setup
cd backend
npm install

Create .env file
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
PORT=5000

Start Backend
npm start


Runs on: http://localhost:5000

💻 Frontend Setup
cd ../frontend
npm install
npm run dev


Runs on: http://localhost:5173

🔌 Socket.io Events
connection
send-message
receive-message
disconnect

📸 Screenshots

(Add your screenshots here)

🌐 Deployment
Frontend:

Vercel

Netlify

Backend:

Render

Railway

Cyclic

Update frontend Axios baseURL with your deployed backend URL.

🤝 Contributing

Pull requests are welcome. Create an issue before major changes.

📜 License

MIT License
