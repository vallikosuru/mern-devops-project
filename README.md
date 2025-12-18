MERN DevOps Project

This project is a simple MERN (MongoDB, Express, React, Node.js) application that runs using Docker and Docker Compose.

It has two services:

Backend → Node.js + Express (Port 5000)

Frontend → React (served using Nginx on Port 3000)MERN DevOps Project

How to Run the Project

Run this command from the project root:

docker compose up -d --build


Stop containers:

docker compose down

📁 Project Structure
mern-devops-project/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── app.js
│   └── Dockerfile
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .env
│   └── Dockerfile.frontend
│
├── docker-compose.yml
├── .dockerignore
└── README.md

