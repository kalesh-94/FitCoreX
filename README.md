#  FitCoreX — Gym Management Application

FitCoreX is a full-stack Gym Management System built with a React (Vite) frontend and a FastAPI backend.
It helps gym owners efficiently manage members, attendance, and fee status through an intuitive UI and a high-performance backend.

---

##  Features

- Member Management  
  Add, view, and update gym member profiles

- Attendance Tracking  
  Record member check-ins and check-outs

- Fee Management  
  Track membership payments and fee status

- Dashboard Analytics  
  Visual charts for insights and reports

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Tailwind CSS
- React Icons

### Backend
- FastAPI
- SQLite Database

---

##  How to Run FitCoreX

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/FitCoreX.git
cd FitCoreX
🔧 Backend Setup (FastAPI)
1. Navigate to the backend folder
cd server

2. Install required Python packages
pip install -r requirements.txt

3. Start the FastAPI backend
uvicorn server:app --reload

📍 Backend will run at:

API Base URL → http://localhost:8000

Swagger Docs → http://localhost:8000/docs

🐍 Optional: Using a Virtual Environment
python -m venv myenv
.\myenv\Scripts\activate.ps1
pip install -r requirements.txt
uvicorn server:app --reload

💻 Frontend Setup (React + Vite)
1. Open a new terminal and navigate to the client folder
cd client

2. Install dependencies
npm install

3. Start the development server
npm run dev

📍 Frontend will run at:
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

⭐ Support the Project

If you find FitCoreX helpful, please consider giving the repository a ⭐ on GitHub — it really helps!

👨‍💻 Author

Kalesh Patil
