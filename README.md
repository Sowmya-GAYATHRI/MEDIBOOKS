# MEDIBOOKS
MediBook - Doctor Appointment Booking System
Overview
MediBook is a full-stack appointment booking application connecting patients with doctors. It features a robust admin dashboard for managing doctors and slots, and a patient portal for booking appointments.

Tech Stack
Backend: Node.js, Express, MongoDB

Frontend: React, Vite, TailwindCSS

Docs: /docs (System Design, Testing Report)
Folder Structure
/backend - API Server
/frontend - React Application
/docs - Project Documentation
Setup & Local Run
Prerequisites
Node.js (v16+)
MongoDB Instance (URI required)
Backend
cd backend
npm install
Create .env based on .env.example
npm start (Runs on port 3000)
Frontend
cd frontend
npm install

Backend: Deploy to any Node.js host (Render, Railway). Set MONGODB_URI.
Frontend: Run npm run build in /frontend. Serve the /dist folder statically (Vercel, Netlify).
Demo Credentials
Admin Login: admin / admin123
Patient: Register via UI
