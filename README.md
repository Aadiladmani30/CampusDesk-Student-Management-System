# CampusDesk Student Management System
React + Vite frontend, Express/Node.js backend, MongoDB database, JWT login.

## Setup
1. Install Node.js and MongoDB (or use MongoDB Atlas).
2. Open this folder in VS Code.
3. In a terminal:
   ```powershell
   cd backend
   npm install
   ```
4. Copy `backend/.env.example` to `backend/.env`, then set `JWT_SECRET` to a long random value.
5. Start MongoDB and run `npm run dev` in the backend terminal.
6. Open a second terminal at the project root:
   ```powershell
   cd frontend
   npm install
   npm run dev
   ```
7. Open the Vite URL shown, usually http://localhost:5173.

## Separate pages
Dashboard, Add Student, View Students, Assign Task, Attendance.
API: `/api/auth`, `/api/students`, `/api/tasks`, `/api/attendance`.
Student/task/attendance routes require a JWT Bearer token. Keep `.env` private.
