## 🏋️‍♂️ FitCoreX — Gym Management Application

FitCoreX is a full-stack Gym Management system built with a React (Vite) frontend and a FastAPI backend. It helps manage gym members, attendance, and fee status through an intuitive interface and a fast backend.

✨ Features

Member Management – Add, view, and update member profiles

Attendance Tracking – Record check-ins and check-outs

Fee Management – Track membership payments

Dashboard Analytics – Visual charts for insights

🛠️ Tech Stack
Frontend

React (Vite)

TypeScript

Tailwind CSS

React Icons

Backend

FastAPI

SQLite database

🚀 How to Run FitCoreX (Without Docker)
1. Clone the Repository
git clone https://github.com/your-username/FitCoreX.git
cd FitCoreX

🔧 Backend Setup (FastAPI)



1. Navigate to backend folder:
cd server

2. Install required Python packages:
pip install -r requirements.txt

3. Start the FastAPI backend:
uvicorn server:app --reload

Backend will run at:

API Base URL → http://localhost:8000

API Docs (Swagger) → http://localhost:8000/docs


if you need virtual environment use
1- python -m venv myenv
2- .\myenv\Scripts\activate.ps1
3- pip install -r requirements.txt
4- uvicorn server:app --reload




💻 Frontend Setup (React + Vite)
1. Open a new terminal and go to the client folder:
cd client

2. Install dependencies:
npm install

3. Start development server:
npm run dev

Frontend will run at:

http://localhost:3000

📁 Project Structure
FitCoreX/
├── client/                 # React frontend
├── server/                 # FastAPI backend
├── db.db                   # SQLite database
├── requirements.txt        # Backend dependencies
└── README.md               # Documentation

📋 API Endpoints (Backend Summary)

Visit Swagger Docs → http://localhost:8000/docs

Members

POST /add_member — Add a new member

GET /members — Get all members

POST /update_fee_status — Update payment/fee status

Attendance

POST /record_attendance — Mark check-in or check-out

GET /attendance — List attendance records
