# Job Board App - Backend

This is the backend for the Job Board App, built using **Node.js**, **Express**, and **MongoDB**.

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS

## 🚀 Getting Started

1. Clone the repository
git clone https://github.com/ayush7078/Job-board-app-backend.git
cd Job-board-app-backend

2. Install dependencies
npm install

3. Configure Environment
Create a .env file in the root with the following:
env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/job-board

4. Start the server
npm run dev
The server will run at http://localhost:5000.

📁 Project Structure
job-board-app-backend/
├── controllers/
├── models/
├── routes/
├── .env
├── server.js
└── package.json

📡 API Endpoints
GET /api/jobs - Get all jobs
POST /api/jobs - Add a new job
GET /api/jobs/:id - Get a single job by ID

