
# BookNest - MERN Bookstore Web Application

**BookNest** is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). It provides users with the ability to register, log in, browse books, add them to a cart, and simulate placing orders. The app is designed for clarity, simplicity, and scalability — ideal for both learning and production scaffolds.


<img width="1440" alt="Screenshot 2025-06-30 at 3 48 45 PM" src="https://github.com/user-attachments/assets/4d3fa1bb-8788-4ff4-983e-a74db4bd893d" />





## BookNest DEMOVIDEO
drivelink:https://drive.google.com/file/d/1ndEgufrAFmAInQ7BBVicm3oaxXW4tb2e/view?usp=drive_link


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

## Screenshots 
signup page
<img width="1440" alt="Screenshot 2025-06-30 at 3 49 10 PM" src="https://github.com/user-attachments/assets/93d35554-9315-4d0b-9261-bb033bdb6949" />
signin page
<img width="1440" alt="Screenshot 2025-06-30 at 3 49 33 PM" src="https://github.com/user-attachments/assets/99d7816b-7595-4d0c-8600-daab917f99e6" />
home page
<img width="1440" alt="Screenshot 2025-06-30 at 3 48 45 PM" src="https://github.com/user-attachments/assets/d96167a9-06be-4956-a16e-594b8ae29cdc" />
book page
<img width="1440" alt="Screenshot 2025-06-30 at 4 21 49 PM" src="https://github.com/user-attachments/assets/1a3f83eb-16d6-4808-85e3-888db066287a" />
wishlist
<img width="1440" alt="Screenshot 2025-06-30 at 4 22 16 PM" src="https://github.com/user-attachments/assets/59b9f8be-a6fc-4b5b-bb87-057213f68bf9" />
seaching book
<img width="1440" alt="Screenshot 2025-06-30 at 4 22 55 PM" src="https://github.com/user-attachments/assets/26f00fda-ded0-40e4-bb4f-0365331497b2" />
cart 
<img width="1440" alt="Screenshot 2025-06-30 at 4 22 26 PM" src="https://github.com/user-attachments/assets/59528d4b-921d-45d0-829a-2e552c599cfe" />
my orders
<img width="1440" alt="Screenshot 2025-06-30 at 4 22 21 PM" src="https://github.com/user-attachments/assets/dbb66c2b-abc7-4b54-8216-ab27e6dcab80" />
admin dashbord
<img width="1440" alt="Screenshot 2025-06-30 at 4 20 22 PM" src="https://github.com/user-attachments/assets/e2673590-0931-4e47-9fb0-69b38088cf51" />
new book adding page
<img width="1440" alt="Screenshot 2025-06-30 at 4 20 33 PM" src="https://github.com/user-attachments/assets/9b972b59-9bcc-4caf-a174-eca60042fd14" />


## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software.

---

## Author

**Pujith Kommindala**  
GitHub: [https://github.com/pujith-k](https://github.com/pujith-k)

---

## Support

If you found this project useful, consider giving it a ⭐️ on GitHub.
