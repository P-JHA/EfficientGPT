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

```bash id="wzzj8m"
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

```env id="k9vxyq"
OPENAI_API_KEY=your_openai_api_key
MONGODB_URI=your_mongodb_connection_string
```

## Default Ports

The project runs on the following default ports during local development:

* Frontend (Vite Development Server): `http://localhost:5173`
* Backend (Express Server): `http://localhost:8080`

> Note: The backend port is currently configured directly inside `server.js`.

## Installation and Setup

### Clone the repository

```bash id="g5ut2u"
git clone https://github.com/your-username/EfficientGPT.git
cd EfficientGPT
```

### Backend Setup

```bash id="2m1e7n"
cd Backend
npm install
node server.js
```

Backend runs on:

```bash id="jlwmn9"
http://localhost:8080
```

### Frontend Setup

Open another terminal

```bash id="t4yxdr"
cd Frontend
npm install
npm run dev
```

Frontend runs on:

```bash id="5f4gk7"
http://localhost:5173
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
