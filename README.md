# 🌌 Solar System Docker Project
<img width="1896" height="889" alt="Screenshot 2025-07-24 113025" src="https://github.com/user-attachments/assets/70e406b8-a5cb-46e5-969f-1b166bf59da4" />

This is a simple Node.js project that allows users to enter a number and get the name of the corresponding planet in our solar system. The application is containerized using Docker and uses MongoDB for backend data storage.

## 🛠 Technologies Used

- Node.js
- MongoDB
- Docker
- Docker Compose

---

## 🐳 How to Run Using Docker

# Solar System Docker Setup

## 1. Clone the Repository

```bash
git clone https://github.com/Abdelrahman-shebl/Solar-System-Docker.git
cd Solar-System-Docker
```

## 2. 🚀 Build and Start Containers
Make sure Docker is installed and running on your system.

```bash
docker-compose up --build
```

This will:

Build your Node.js app container.

Start a MongoDB container.

Connect both services together.

## 3. 🌐 Access the Application
```bash
http://localhost:3000
```

You can then enter a number (e.g. 1 → Mercury, 2 → Venus, etc.).






