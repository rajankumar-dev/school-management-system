# 🏫 School Management System  

A full-stack **School Management System** built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and enhanced with modern tools for authentication, state management, form handling, and more.  

This project provides a complete solution for managing school operations, including student/teacher management, authentication, file uploads, and secure API interactions.  

---

## 🚀 Tech Stack  

### 🌐 Frontend  
- **React.js** – Component-based UI  
- **React Router** – Client-side routing  
- **Axios** – HTTP requests to server  
- **Formik + Yup** – Form handling & validation  
- **React-Redux + Redux Toolkit** – State management  

### ⚙️ Backend  
- **Node.js + Express.js** – Server-side logic & APIs  
- **MongoDB (Mongoose)** – Database for storing school data  
- **jsonwebtoken (JWT)** – Authentication & authorization  
- **bcrypt** – Password hashing  
- **formidable** – File upload handling  

---

## 🔑 Features  

✅ **Responsive UI**
✅ **User Authentication & Authorization** (JWT-based)  
✅ **Secure Passwords** with Bcrypt encryption  
✅ **Protected Routes** – only accessible to authorized users  
✅ **Student & Teacher Management** (CRUD operations)  
✅ **Form Handling with Validation** (Formik + Yup)  
✅ **Global State Management** using Redux Toolkit  
✅ **File Upload Support** (e.g., student profile pics, documents)  
  

---

## 📂 Project Structure  

```
school-management-system/
│
├── client/             # React frontend
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── pages/      # Different pages (login, dashboard, etc.)
│   │   ├── redux/      # State management
│   │   ├── utils/      # Helper functions
│   │   └── App.js
│   └── package.json
│
├── server/             # Express backend
│   ├── config/         # DB & JWT config
│   ├── controllers/    # Route controllers
│   ├── middleware/     # Auth & error handling
│   ├── models/         # MongoDB models
│   ├── routes/         # API routes
│   └── server.js
│
└── README.md
```

---

## ⚡ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/school-management-system.git
cd school-management-system
```

### 2️⃣ Install dependencies  

**Backend**  
```bash
cd server
npm install
```

**Frontend**  
```bash
cd client
npm install
```

### 3️⃣ Setup environment variables  
Create a `.env` file in the **server** directory:  
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the application  

**Backend**  
```bash
cd server
npm start
```

**Frontend**  
```bash
cd client
npm start
```

---

## 📸 Screenshots (Optional)  
![Dashboard](https://github.com/rajankumar-dev/school-management-system/blob/main/screenshoots/Screenshot%202025-09-08%20201635.png)
![Subject](https://github.com/rajankumar-dev/school-management-system/blob/main/screenshoots/Screenshot%202025-09-08%20205021.png)
![Class](https://github.com/rajankumar-dev/school-management-system/blob/main/screenshoots/Screenshot%202025-09-08%20205041.png)
![Weekly Report](https://github.com/rajankumar-dev/school-management-system/blob/main/screenshoots/Screenshot%202025-09-08%20205136.png)

---

## 🔮 Future Enhancements  
- Role-based access control (Admin, Teacher, Student)  
- Attendance & Grade management  
- Notifications & Announcements module  
- Deployment on **Vercel/Netlify (Frontend)** & **Render/Heroku (Backend)**  

---

## 🤝 Contributing  
Contributions are welcome! Please fork the repo and create a pull request.  

---

## 📜 License  

This project is licensed under the **MIT License** – you are free to use, modify, and distribute this project with proper attribution.  
