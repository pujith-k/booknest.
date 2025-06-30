
# BookNest - MERN Bookstore Web Application

**BookNest** is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). It provides users with the ability to register, log in, browse books, add them to a cart, and simulate placing orders. The app is designed for clarity, simplicity, and scalability — ideal for both learning and production scaffolds.


<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/0f922f39-6248-4e83-9452-0d6a62ccfc49" />

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots-optional)
- [License](#license)
- [Author](#author)

---

## Features

- Secure user authentication with JWT
- Browse and display list of available books
- Add/remove books to/from a shopping cart
- Simulate order placement and view order summary
- Clean and responsive user interface
- Modular backend with clear route/controller structure
- MongoDB database integration
- Optional admin support for managing books

---

## Tech Stack

| Layer        | Technology                      |
|--------------|----------------------------------|
| Frontend     | React, React Router, Axios       |
| Backend      | Node.js, Express.js              |
| Database     | MongoDB, Mongoose                |
| Authentication | JSON Web Tokens (JWT), bcrypt |
| Development  | Nodemon, concurrently            |

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/pujith-k/booknest.git
cd booknest
```

### Step 2: Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

---

## Environment Variables

Create a `.env` file inside the `backend/` directory with the following contents:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

Replace `your_mongodb_connection_string` and `your_jwt_secret_key` with your actual credentials.

---

## Running the Application

### Backend

```bash
cd backend
npm start
```

Runs on: `http://localhost:5000`

### Frontend

```bash
cd frontend
npm start
```

Runs on: `http://localhost:3000`

---

## Project Structure

```
booknest/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
├── README.md
└── package.json
```

---

## Screenshots (Optional)



## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software.

---

## Author

**Pujith Kommindala**  
GitHub: [https://github.com/pujith-k](https://github.com/pujith-k)

---

## Support

If you found this project useful, consider giving it a ⭐️ on GitHub.
