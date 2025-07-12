# 📚 MERN School Management System

<img width="1297" height="746" alt="image" src="https://github.com/user-attachments/assets/98fc7fc9-50b7-457b-812a-e7439a74f689" />

A complete School Management System built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This system helps manage students, teachers, classes, assignments, announcements, events, and library records.

---

## 🛠 Tech Stack

- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Other Tools**: Postman, Git, GitHub, Nodemon, Dotenv

---

## ✨ Features

- ✅ Student Management (CRUD operations)
- ✅ Teacher Management
- ✅ Class Assignments
- ✅ Event Announcements
- ✅ Library Book Records
- ✅ MongoDB Database Integration
- ✅ REST API using Express.js
- ✅ Clean and Responsive UI using React


## 🚀 How to Run the Project

### Prerequisites

- Node.js installed
- MongoDB running locally or MongoDB Atlas cluster
- Git

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YarragorlaKiranmayee/Mern_School_Management_System.git
cd Mern_School_Management_System
````

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

* Create a `.env` file and add:

```env
PORT=4000
MONGO_URI=mongodb+srv://kiranmayee:kiranmayee@cluster0.4dxqeid.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
```

* Start the backend server:

```bash
npm start
```

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

Frontend will be served at: [http://localhost:3000](http://localhost:3000)
Backend runs at: [http://localhost:4000](http://localhost:4000)

---

## 🧪 API Endpoints (Sample)

### Students

* `GET /api/v1/students`
* `POST /api/v1/students`
* `PUT /api/v1/students/:id`
* `DELETE /api/v1/students/:id`

> Use Postman or other tools to test the APIs

## 📌 TODO / Future Enhancements

* Authentication (Login/Signup)
* Role-based Access (Admin, Teacher, Student)
* Notifications
* PDF Reports Generation

---

## 🙌 Contributors

* [Kiranmayee Yarragorla](https://github.com/YarragorlaKiranmayee)

---
