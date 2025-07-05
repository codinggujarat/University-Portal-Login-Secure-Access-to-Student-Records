# 🎓 University Login System
A secure and containerized university login portal that allows users to authenticate and view their academic or personal details retrieved from a MongoDB database. This system uses **Node.js** for backend logic, **MongoDB** for data storage, **Docker** for containerization, and **HTML/CSS** for a clean and responsive frontend.
## 🚀 Features
- 🔐 Secure login authentication
- 📦 MongoDB database integration
- 🧩 Modular Node.js Express backend
- 🌐 Responsive HTML login page
- 🐳 Dockerized for easy deployment and scalability
## 🛠️ Tech Stack
- **Node.js** – Server-side logic and API routes
- **Express.js** – Web framework for routing and middleware
- **MongoDB** – NoSQL database for storing user data
- **Docker** – Containerization of the app and database
- **HTML/CSS** – Frontend interface

## ⚙️ Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/your-username/university-login.git
cd university-login
```
### 2. Configure Environment Variables
Create a `.env` file in the `backend/` directory:
```
PORT=5000
MONGO_URI=mongodb://mongo:27017/university
```
### 3. Start the application using Docker
```bash
docker-compose up --build
```
The frontend will be available at `http://localhost:3000` and backend at `http://localhost:5000`.
## 🧪 Usage
1. Open your browser and go to `http://localhost:3000`
2. Enter your login credentials (from seeded MongoDB data)
3. On success, you'll be redirected to a page showing your university profile and academic data
## 📌 Notes
- Make sure Docker is installed and running
- MongoDB is seeded with sample user data during container initialization
.
## 🙋‍♂️ Author
Made by [AMAN] 