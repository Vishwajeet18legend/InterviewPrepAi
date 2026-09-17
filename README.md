# 🚀 InterviewPrepAI

### AI-Powered Interview Preparation Platform

InterviewPrepAI is a full-stack **MERN application** designed to help students and job seekers prepare for technical interviews through personalized interview sessions, questions, answers, notes, and AI-powered features.

The project provides a structured platform where users can create and manage interview preparation sessions while keeping their questions and learning progress organized.

---

## ✨ Features

### 🔐 Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- User Profile
- Profile Image Upload

### 📚 Interview Session Management

- Create Interview Sessions
- View All Sessions
- View Individual Sessions
- Delete Sessions
- Organize interview preparation by session

### ❓ Question Management

- Add Interview Questions
- Add Answers
- Pin Important Questions
- Add Personal Notes
- Review questions inside interview sessions

### 🤖 AI Integration

AI-powered features are planned using the **Google Gemini API**, including:

- AI Question Generation
- AI-Powered Explanations
- Personalized Interview Preparation
- Mock Interview System

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Tailwind CSS
- JavaScript

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer

## AI

- Google Gemini API *(Upcoming)*

---

# 📁 Project Structure

```text
InterviewPrepAi/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   └── interview-prep-ai/
│       ├── src/
│       ├── public/
│       └── package.json
│
├── .gitignore
└── README.md
⚙️ Getting Started
1. Clone the Repository
git clone https://github.com/Vishwajeet18legend/InterviewPrepAi.git

Navigate into the project:

cd InterviewPrepAi
🔧 Backend Setup

Navigate to the backend:

cd backend

Install dependencies:

npm install

Create a .env file inside the backend folder:

PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Start the backend server:

npm run dev

The backend will run on:

http://localhost:8000
💻 Frontend Setup

Open another terminal and navigate to the frontend:

cd frontend/interview-prep-ai

Install dependencies:

npm install

Start the frontend:

npm run dev

The frontend will normally be available at:

http://localhost:5173
🔑 Environment Variables

The backend requires the following environment variables:

Variable	Description
PORT	Backend server port
MONGO_URI	MongoDB connection string
JWT_SECRET	Secret key used for JWT authentication

⚠️ Never commit your .env file or expose your database credentials and secret keys publicly.

📌 Current Status
✅ Completed
 User Authentication
 JWT Authentication
 Protected Routes
 Profile Image Upload
 Interview Session APIs
 Question APIs
 MongoDB Integration
 Question Pinning
 Notes Management
🚧 Upcoming
 AI Question Generation
 AI-Powered Question Explanations
 Google Gemini API Integration
 Mock Interview System
 Personalized Interview Recommendations
 Interview Performance Tracking
🔗 Repository

GitHub:
https://github.com/Vishwajeet18legend/InterviewPrepAi

👨‍💻 Author
Vishwajeet Raj

CSE (AI & ML) Student
Techno Main Salt Lake, Kolkata

GitHub:
https://github.com/Vishwajeet18legend

⭐ Project

If you find this project useful, consider giving it a ⭐ on GitHub!
