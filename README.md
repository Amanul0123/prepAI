# 🧠 PrepAI

A MERN-based ChatGPT replica implemented from scratch using OpenAI's API.  
This project serves as a smart personal assistant for Computer Science students to get help with coding, concepts, and interview preparation.

---

## 🚀 Features

- 💬 Real-time chat with AI using OpenAI GPT API
- 📚 Tailored for CS students: Get help on coding, algorithms, theory, etc.
- 🖥 Built with the MERN stack:
  - **MongoDB** for chat history (optional)
  - **Express.js** as the backend API layer
  - **React.js** frontend UI
  - **Node.js** for server logic
- 🔐 API key protection with environment variables
- 📄 Chat memory (short-term session-based)
- ✨ Clean and minimal UI (React + CSS)

---

## 📁 Project Structure

PrepAI/
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ └── App.js
├── server/ # Express backend
│ ├── routes/
│ └── server.js
├── .env
├── package.json
└── README.md


---

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/Amanul0123/prepAI.git
cd prepAI

## 2. Set up the Server

cd server
npm install

Create a .env file inside /server with the following:

OPENAI_API_KEY=your_openai_api_key
PORT=5000

## 3. Set up the Client

cd ../client
npm install
npm start

## 4. Run the Server

cd ../server
npm start
Your app should now be running at http://localhost:3000

## 🧪 Tech Stack
Frontend: React, Axios, CSS

Backend: Node.js, Express

API: OpenAI GPT-3.5/4 via REST

Optional: MongoDB (for storing chat history)

## 🧑‍💻 Use Cases
Get instant help on programming questions

Prepare for coding interviews

Learn algorithms and data structures

Debug your code using natural language

## ⚠️ Disclaimer
This project uses OpenAI's API and requires a valid API key. Make sure not to expose your API key publicly.
