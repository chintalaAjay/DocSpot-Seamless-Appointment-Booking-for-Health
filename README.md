# 📅 DocSpot – Seamless Doctor Appointment Booking Platform

**Team ID:** LTVIP2026TMIDS82466  
**Team Size:** 4  

## 👥 Team Members
- **Team Leader:** Bandela Satish  
- **Team Member:** Ajay Chintala  
- **Team Member:** Bala Phani Dhanaraju Kaki  
- **Team Member:** Dasari Sravan  

---

## 🏥 Project Overview
DocSpot is a **full-stack healthcare appointment booking platform** that simplifies the process of connecting patients with doctors.  
Built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**, the application offers real-time scheduling, role-based dashboards, and a smooth, user-friendly experience for **patients, doctors, and administrators**.

---

## 🚀 Features

### 👤 Patients
- Secure registration and login  
- Browse doctors by specialization, location, or availability  
- Book appointments and receive confirmations  
- Upload medical documents (reports, prescriptions)  
- View upcoming and past appointments  
- Cancel or reschedule appointments  

### 🩺 Doctors
- Apply and register for platform access  
- Manage availability and appointment slots  
- View and confirm patient appointments  
- Access uploaded documents  
- Add follow-up notes  

### 🛠️ Admins
- Approve or reject doctor registrations  
- Manage users and monitor system activity  
- Ensure data integrity and platform compliance  

---

## 🏗️ Tech Stack

| Layer | Technology |
|------|-----------|
| Frontend | React.js, Axios, Bootstrap, Material UI |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose) |
| Authentication | JWT, bcrypt |
| Deployment | Vercel (Frontend), Render / Heroku (Backend) |
| Others | Moment.js, dotenv |

---

## 📂 Project Structure

```text
docspot-app/
├── backend/
│   ├── controllers/         # Business logic and route handlers
│   ├── models/              # MongoDB schemas
│   ├── routes/              # REST APIs (auth, users, appointments)
│   ├── middleware/          # JWT auth, error handling, role checks
│   ├── .env                 # Environment variables
│   ├── server.js            # Backend entry point
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── common/      # Header, Footer
│   │   │   ├── user/        # Patient components
│   │   │   ├── doctor/      # Doctor dashboard
│   │   │   └── admin/       # Admin panel
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── README.md
└── vercel.json
⚙️ Setup Instructions
✅ Prerequisites
Node.js (v16+ recommended)

MongoDB (Local or Atlas)

Git

Code Editor (VS Code recommended)

🖥️ Backend Setup
cd backend
npm install
Create a .env file and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Start backend server:

npm start
🌐 Frontend Setup
cd frontend
npm install
npm start
Visit: http://localhost:3000

🌍 Live Demo
🔗 Try the App:
https://docspot-deployment.vercel.app/

🔮 Future Enhancements
🎥 Video Consultation

💳 Online Payment Integration

📄 Prescription Upload & Sharing

⭐ Doctor Ratings & Feedback

📊 Health Records Dashboard

📄 License
This project is licensed under the MIT License.
