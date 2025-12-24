
# 🩺 DocSpot – Doctor Appointment Booking System

DocSpot is a *full stack doctor appointment booking web application* that allows users to register, login, and book appointments with doctors.  
This project is built using the *MERN stack* and demonstrates end-to-end integration of frontend, backend, and database.

---

## 🚀 Features

- User Registration & Login (Authentication)
- Role-based access (User / Doctor / Admin)
- Doctor listing
- Appointment booking system
- Secure backend APIs
- MongoDB database integration

---

## 🛠 Tech Stack

### Frontend
- React.js
- HTML, CSS, JavaScript
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

## 📂 Project Structure

text
DocSpot/
├── frontend/        # React frontend
├── backend/         # Node.js & Express backend
│   ├── config/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── DOCUMENT/        # Project documentation
├── Video Demo/      # Demo video (if any)
├── .gitignore
├── README.md



---

## ⚙ How to Run the Project Locally

 1️⃣ Clone the repository

git clone https://github.com/varshitha211/DocSpot.git
2️⃣ Backend Setup

cd DocSpot/backend
npm install
npm start
Backend runs on:
   http://localhost:8001
3️⃣ Frontend Setup
 
cd ../frontend
npm install
npm start
Frontend runs on:


http://localhost:3000
🔐 Environment Variables
Create a .env file inside backend folder:

Env
MONGO_URI=your_mongodb_connection_string
PORT=8001
⚠ .env file is ignored using .gitignore for security.

🎯 Future Enhancements
Appointment approval & cancellation
Doctor availability scheduling
Admin dashboard improvements
Deployment on cloud platforms
👩‍💻 Author
Amara Krupa Varshitha
Full Stack Developer | MERN Stack Enthusiast
