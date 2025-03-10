# Fullstack Chat App

A real-time full-stack chat application with authentication, message storage, and image support. Built with **MERN Stack (MongoDB, Express, React, Node.js)** and Socket.io for real-time messaging.

## 🚀 Features
- User authentication (Login/Register)
- Real-time messaging with WebSockets
- Image upload via Cloudinary
- Sidebar with online users
- Responsive UI with modern design

## 🛠 Tech Stack
- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Socket.io
- **Database:** MongoDB (Mongoose ORM)
- **Cloud Storage:** Cloudinary for image uploads
- **Authentication:** JWT & Cookie-based auth

## 📂 Folder Structure
```
📦 fullstack-chat-app
├── 📂 backend        # Node.js & Express server
│   ├── 📂 models     # Database models (User, Message)
│   ├── 📂 routes     # API routes
│   ├── 📂 controllers # Business logic
│   ├── 📂 lib        # Utilities (DB, Socket, Cloudinary)
│   ├── index.js     # Main backend entry point
│
├── 📂 frontend       # React application
│   ├── 📂 src
│   │   ├── 📂 components   # Reusable UI components
│   │   ├── 📂 pages        # Screens (Login, Chat, etc.)
│   │   ├── 📂 store        # State management (Zustand, Redux, or Context API)
│   │   ├── main.jsx       # React entry point
│
└── README.md
```

## 🛠 Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/abhaydubey200/fullstack-chat-app.git
cd fullstack-chat-app
```

### 2️⃣ Install dependencies
#### Backend
```sh
cd backend
npm install
```
#### Frontend
```sh
cd ../frontend
npm install
```

### 3️⃣ Set up environment variables
Create a **.env** file in the `backend/` directory with:
```ini
PORT=5001
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4️⃣ Start the development server
#### Backend
```sh
cd backend
npm start
```
#### Frontend
```sh
cd frontend
npm run dev
```

## 🚀 Usage
1. Register a new user or log in.
2. Start a chat with any user in the sidebar.
3. Send text messages and images.

## 🛠 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/auth/register` | Register a new user |
| `POST` | `/api/auth/login` | Login user |
| `GET` | `/api/messages/:id` | Get messages with a user |
| `POST` | `/api/messages/send/:id` | Send a message |

## 🔥 Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Added new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

## 📜 License
This project is **MIT Licensed**.

## 📩 Contact
For inquiries, contact [Abhay Dubey](mailto:dubeyabhay430@gmail.com).

