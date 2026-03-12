# 📚 MERN Book Store Web Application

A full-stack **Book Store Web Application** built using the **MERN Stack (MongoDB, Express, React, Node.js)**.  
This platform allows users to browse free books and securely access premium content through authentication.

The project focuses on providing a **modern user experience** with dynamic UI components, responsive design, theme switching (Dark/Light Mode), and secure backend integration.

---

# 🚀 Features

### 📖 Book Browsing
- Browse and display a collection of free books
- Clean and organized book card layout

### 🔐 Authentication System
- User Signup and Login functionality
- Secure password hashing using **bcrypt**
- Authentication state management using **React Context**

### 🎞️ Dynamic Homepage
- Interactive book slider highlighting featured books

### 🌗 Dark / Light Mode
- Toggle between dark and light themes for improved user experience

### 🧭 Smooth Navigation
- Client-side routing using **React Router DOM**

### ✅ Form Validation
- Form handling using **React Hook Form**
- Prevents invalid inputs on the client side

### 📱 Responsive Design
- Fully responsive UI for desktop, tablet, and mobile devices
- Responsive footer and layout components

### 🌐 REST API Integration
- Communication between frontend and backend using REST APIs

### ⚠️ CORS Handling
- Proper configuration for frontend-backend communication

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Tailwind CSS
- React Router DOM
- React Hook Form

## Backend
- Node.js
- Express.js

## Database
- MongoDB

## Authentication & Security
- bcrypt.js

---

# 📂 Project Structure

```
mern-bookstore
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   ├── App.js
│   │   └── index.js
│
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── server.js
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1. Clone the repository

```bash
git clone https://github.com/yourusername/mern-bookstore.git
cd mern-bookstore
```

## 2. Install Backend Dependencies

```bash
cd backend
npm install
```

## 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

## 4. Setup Environment Variables

Create a `.env` file inside the **backend** folder.

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 5. Run the Application

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm start
```

The application will run at:

```
Frontend: http://localhost:3000
Backend: http://localhost:5000
```

---

# 📸 Screenshots

You can add screenshots of your application here.

Example:

```
![Homepage](screenshots/home.png)
![Login Page](screenshots/login.png)
```

---

# 🌟 Future Improvements

- Payment gateway integration
- Admin dashboard for managing books
- Book search and filtering
- User profile management
- Book ratings and reviews

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

---

# 👨‍💻 Author

**Sujal Bhardwaj**

GitHub: https://github.com/sujal-io

