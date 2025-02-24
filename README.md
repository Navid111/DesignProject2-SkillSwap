# SkillSwap

SkillSwap is a peer-to-peer learning platform that allows users to swap skills and connect with each other for mutual learning.

## Project Structure
SkillSwap/
├── backend/
│   ├── config/               # (For future configuration files)
│   ├── controllers/          # (For your route handlers/business logic)
│   ├── models/               # (For Mongoose models)
│   ├── routes/               # (For API route definitions)
│   ├── .env.example          # (Example env file; copy to .env and add your credentials)
│   ├── package.json          # (Backend dependencies and scripts)
│   └── server.js             # (Main Express server file)
├── frontend/
│   ├── public/               # (Static assets, HTML, etc.)
│   ├── src/
│   │   ├── components/       # (Reusable React components)
│   │   ├── App.js            # (Main React component)
│   │   └── index.js          # (Entry point for React)
│   └── package.json          # (Frontend dependencies and scripts)
└── README.md                 # (Project overview and setup instructions)

## Getting Started

### Backend

1. Navigate to the `backend` directory:
cd backend
2. Install dependencies:
npm install
3. Create a `.env` file by copying `.env.example` and set your MongoDB connection string:
cp .env.example .env
4. Start the server:
npm run dev

### Frontend

1. Navigate to the `frontend` directory:
cd frontend
2. Install dependencies:
npm install
3. Start the development server:
npm start
