# 🔐 Auth App

A full-stack authentication system with user registration, login, JWT-based authentication, and protected routes.

---

## 🚀 Features

* 📝 User Registration
* 🔑 Login Authentication
* 🔒 Password hashing using bcrypt
* 🪙 JWT Token-based authentication
* 🛡️ Protected routes (middleware)
* 💻 Simple frontend (HTML, CSS, JS)

---

## 🛠️ Tech Stack

* Backend: Node.js, Express.js
* Database: MongoDB (Mongoose)
* Authentication: JWT (jsonwebtoken)
* Security: bcryptjs
* Frontend: HTML, CSS, JavaScript

---

## 📂 Project Structure

```
auth-app/
│
├── config/
│   └── db.js
├── models/
│   └── User.js
├── routes/
│   └── auth.js
├── middleware/
│   └── authMiddleware.js
├── .env
├── server.js
├── index.html
├── login.html
├── register.html
├── dashboard.html
```

---

## ⚙️ Installation & Setup

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/auth-app.git
cd auth-app
```

2. Install dependencies

```
npm install
```

3. Create a `.env` file

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

4. Run the server

```
npm run dev
```

5. Open frontend

* Right click `index.html`
* Open with Live Server

---

## 🔐 API Endpoints

### Register

```
POST /api/auth/register
```

### Login

```
POST /api/auth/login
```

### Protected Route

```
GET /api/dashboard
```

---

## 📸 Screenshots

### Home Page
![Home](https://github.com/user-attachments/assets/8bd05b59-eea0-40fa-a034-6d6dea7cd923)

### Register Page
![Register](https://github.com/user-attachments/assets/07aeb193-bbb6-46a6-bdbd-7a5051acda0b)

### Login Page
![Login](https://github.com/user-attachments/assets/6275f83f-36b9-4ec6-89df-bf11d4a7c2b7)

### Dashboard
![Dashboard](https://github.com/user-attachments/assets/ba0d2da5-53cf-473a-9ceb-3965ad7feb75)

---

## 🌟 Future Improvements

* Add user profile page
* Improve UI/UX
* Convert frontend to React
* Deploy backend & frontend

---

## 👩‍💻 Author

Chandini
