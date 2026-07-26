# 🎥 MERN Video Calling Application

A full-stack real-time video calling application built using the MERN Stack. The application enables users to register, authenticate securely, make one-to-one video calls, exchange messages, manage friends, and maintain call history with a responsive and user-friendly interface.

---

## 🚀 Features

- 🔐 User Authentication (JWT Authentication)
- 👤 User Registration & Login
- 📝 User Profile Management
- 👥 Add & Manage Friends
- 💬 Real-time Chat
- 📹 One-to-One Video Calling
- 📞 Call Notifications
- 📜 Call History
- 🟢 Online/Offline User Status
- 🔔 Real-time Updates using Socket.IO
- 📱 Fully Responsive UI

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios
- Context API

### Backend
- Node.js
- Express.js
- JWT Authentication
- bcrypt.js
- Socket.IO

### Database
- MongoDB
- Mongoose

### Video Calling
- Stream Video SDK *(or replace with the SDK/service you actually used)*

---

## 📂 Project Structure

```
video-calling-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── socket/
│   ├── config/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/video-calling-app.git
```

```bash
cd video-calling-app
```

---

### Install Backend Dependencies

```bash
cd server
npm install
```

---

### Install Frontend Dependencies

```bash
cd ../client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the server folder.

Example:

```env
PORT=5000

MONGO_URI=Your_MongoDB_URI

JWT_SECRET=Your_JWT_Secret

STREAM_API_KEY=Your_Stream_API_Key

STREAM_API_SECRET=Your_Stream_API_Secret

NODE_ENV=development
```

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

Application will run on

Frontend:

```
http://localhost:5173
```

Backend:

```
http://localhost:5000
```

---

## 🔒 Authentication Flow

- User Registration
- Login with Email & Password
- JWT Token Generation
- Protected Routes
- Secure Password Hashing using bcrypt

---

## 📹 Video Calling Workflow

1. User logs in.
2. Connects with friends.
3. Selects a friend.
4. Initiates a video call.
5. Receiver receives call notification.
6. Secure real-time video communication begins.
7. Call history is stored after completion.

## 🎯 Future Improvements

- Group Video Calls
- Screen Sharing
- Voice Calls
- File Sharing
- Message Reactions
- Push Notifications
- Dark Mode
- Recording Calls

---

## 📚 Learning Outcomes

This project helped in understanding:

- MERN Stack Development
- REST API Development
- JWT Authentication
- Socket.IO Real-time Communication
- Video Calling Integration
- State Management
- Database Design
- Responsive UI Development

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Aishwarya Jaiswal**

- GitHub: https://github.com/Aishwarya844101

---

⭐ If you found this project useful, please give it a Star on GitHub!