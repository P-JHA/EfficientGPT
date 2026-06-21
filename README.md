# EfficientGPT

EfficientGPT is a full-stack AI powered chat application built using the MERN stack. It provides users with an interactive chatbot experience powered by OpenAI while storing chat history and managing backend communication efficiently through MongoDB.

## Features

* AI powered chatbot integration using OpenAI API
* Real-time chat interaction with intelligent responses
* Secure backend API handling using Node.js and Express.js
* Database integration with MongoDB for storing chat data
* Responsive frontend built with React and Vite
* Context management for maintaining chat state
* Modular backend architecture for scalability and maintainability

## Tech Stack

### Frontend

* React.js
* Vite
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### APIs & Tools

* OpenAI API
* Git & GitHub

## Project Structure

```bash
EfficientGPT/
│
├── Backend/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

## Environment Variables

Create a `.env` file inside the Backend folder.

```env
OPENAI_API_KEY=your_openai_api_key
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

## Installation and Setup

### Clone the repository

```bash
git clone https://github.com/your-username/EfficientGPT.git
cd EfficientGPT
```

### Backend Setup

```bash
cd Backend
npm install
node server.js
```

### Frontend Setup

Open another terminal

```bash
cd Frontend
npm install
npm run dev
```

## Future Improvements

* User authentication system
* Multiple chat sessions
* Chat history storage and retrieval
* Dark mode support
* Better UI/UX improvements
* Deployment on cloud platform

## Learning Outcomes

This project helped in understanding:

* MERN stack development
* API integration and handling
* Environment variable management using `.env`
* Secure credential management with `.gitignore`
* Full stack project architecture
* Git and GitHub workflow

## Author

**Prabhakar Jha**

GitHub: https://github.com/P-JHA
