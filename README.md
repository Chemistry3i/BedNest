# BED Nest 🛏️

BED Nest is a full-stack hostel booking and management platform built using the MERN stack.  
It provides a scalable, role-based system for managing hostels, rooms, and bookings with dedicated dashboards for Super Admin, Admin, Hostel Owners, and Users.

## 🚀 Features

### 🔐 Role-Based Access Control
- **Super Admin**: Create and manage Admins, platform-level control
- **Admin**: Approve hostel owners, manage users and hostels
- **Hostel Owner**: Manage hostels, rooms, pricing, and bookings
- **User**: Browse hostels, book rooms, and manage bookings

### 🏨 Hostel & Room Management
- Add and manage hostels
- Room and bed availability tracking
- Pricing management

### 📅 Booking System
- Real-time room availability
- Booking status tracking
- Booking history for users

### 📊 Dashboards
- Admin and owner dashboards
- Booking and occupancy insights

### 🔐 Authentication
- JWT-based authentication
- Secure password hashing
- Protected routes based on user roles

---

## 🛠 Tech Stack

**Frontend**
- React.js
- React Router
- Axios
- Bootstrap / CSS

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT & bcrypt

---

## 📁 Project Structure

```bash
bed-nest/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── services/
│   │   └── App.js
│
└── README.md
