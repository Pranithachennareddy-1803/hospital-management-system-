# 🏥 Hospital Management System

<div align="center">

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Status](https://img.shields.io/badge/Status-Active-success)

*A modern, secure, and scalable Hospital Management System designed to streamline healthcare operations through role-based access, real-time management, and an intuitive user experience.*

</div>

---

# 📖 Overview

Hospital Management System is a full-stack web application that digitizes hospital workflows by providing dedicated portals for **Admin**, **Doctor**, and **Patient**. The platform simplifies appointment scheduling, patient record management, doctor availability, billing, prescriptions, and overall hospital administration.

---

# ✨ Key Features

## 👨‍💼 Admin Portal

- Dashboard with hospital analytics
- Doctor management
- Patient management
- Appointment management
- Department management
- Billing management
- User authentication
- Reports & analytics
- Hospital settings

---

## 👨‍⚕️ Doctor Portal

- Doctor dashboard
- View appointments
- Manage patient records
- Digital prescriptions
- Medical history
- Diagnosis management
- Treatment plans
- Profile management

---

## 🧑‍🤝‍🧑 Patient Portal

- Secure registration & login
- Book appointments
- View doctor availability
- Medical history
- Download prescriptions
- Billing & payment history
- Profile management
- Appointment tracking

---

# 🛠 Tech Stack

## Frontend

- React.js
- Tailwind CSS
- React Router
- Axios
- Framer Motion

## Backend

- Node.js
- Express.js
- JWT Authentication
- REST APIs
- Multer

## Database

- MongoDB
- Mongoose

## Tools

- Git
- GitHub
- VS Code
- Postman

---

# 🏗 System Architecture

```
                Client (React)

                      │

               REST API (Express)

                      │

        Authentication (JWT Middleware)

                      │

     Business Logic & Controllers

                      │

          MongoDB Database
```

---

# 📂 Project Structure

```
Hospital-Management-System/

│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── services/
│   │   ├── context/
│   │   └── assets/
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── uploads/
│
├── package.json
├── README.md
└── .env
```

---

# 🔐 Authentication

- JWT Authentication
- Password Hashing (bcrypt)
- Protected Routes
- Role-Based Access Control (RBAC)

Roles:

- Admin
- Doctor
- Patient

---

# 📊 Modules

### Authentication Module

- Login
- Register
- Forgot Password
- Reset Password

### Appointment Module

- Book Appointment
- Reschedule
- Cancel
- Status Tracking

### Patient Module

- Medical Records
- Reports
- Prescriptions
- History

### Doctor Module

- Availability
- Consultation
- Diagnosis
- Prescription Generation

### Billing Module

- Invoice Generation
- Payment History
- Billing Reports

---

# 💻 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Hospital-Management-System.git
```

## Frontend

```bash
cd client
npm install
npm run dev
```

## Backend

```bash
cd server
npm install
npm run dev
```

---

# ⚙ Environment Variables

Create a `.env` file.

```
PORT=5000

MONGODB_URI=

JWT_SECRET=

CLOUDINARY_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_SECRET=
```

---

# 🚀 API Modules

- Authentication API
- Doctor API
- Patient API
- Appointment API
- Billing API
- Prescription API

---

# 📸 Screens

- Login
- Dashboard
- Doctor Portal
- Patient Portal
- Admin Dashboard
- Appointment Page
- Billing
- Medical Records

---

# 🔒 Security

- JWT Authentication
- Password Encryption
- Role-Based Authorization
- Input Validation
- API Protection
- Secure File Uploads

---

# 📈 Future Enhancements

- AI Disease Prediction
- AI Chat Assistant
- Video Consultation
- Lab Management
- Pharmacy Management
- Insurance Management
- SMS Notifications
- Email Notifications
- QR-Based Patient Check-in
- Multi-Hospital Support
- Inventory Management
- Analytics Dashboard

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

### ⭐ Star this repository if you found it useful!

Made with ❤️ using React, Node.js, Express & MongoDB

</div>
