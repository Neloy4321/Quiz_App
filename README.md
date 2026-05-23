# Quiz App

A full-stack Quiz Application built using Node.js, Express.js, MongoDB, HTML, CSS, and JavaScript.

---

## Features

- User Registration & Login
- Quiz Question System
- Timer Functionality
- MongoDB Integration
- REST API Backend
- Dynamic Quiz Handling

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

---

## Project Structure

```text
Quiz_app-master/
│
├── client/
│   ├── index.html
│   ├── signup.html
│   ├── quiz.html
│   ├── css/
│   └── js/
│
├── server/
│   ├── app.js
│   ├── package.json
│   ├── seedQuestions.js
│   ├── config/
│   ├── models/
│   └── routes/
│
└── README.md
```

---

## Requirements

Before running the project, install:

- Node.js
- MongoDB
- Visual Studio Code (Optional)

---

## Installation & Setup

### 1. Open Project Folder

Open the project folder in VS Code.

---

### 2. Open Terminal

```bash
cd server
```

---

### 3. Install Dependencies

```bash
npm install
```

---

### 4. Start MongoDB

Make sure MongoDB service is running.

---

### 5. Seed Quiz Questions (Optional)

```bash
node seedQuestions.js
```

Run this only once if quiz questions are not available.

---

### 6. Run the Server

```bash
node app.js
```

OR

```bash
npx nodemon app.js
```

---

## Open the Application

Visit:

```text
http://localhost:5000
```

---

## API Routes

### Authentication

```text
POST /api/auth/signup
POST /api/auth/login
```

### Quiz

```text
GET /api/quiz/questions
```

---

## MongoDB Connection

```text
mongodb://127.0.0.1:27017/quiz-app
```

---

## Common Errors & Fixes

### MongoDB Connection Error

Problem:

```text
MongoNetworkError
```

Solution:

Start MongoDB service.

---

### Module Not Found

Problem:

```text
Cannot find module
```

Solution:

```bash
npm install
```

---

### Port Already in Use

Problem:

```text
EADDRINUSE
```

Solution:

Change the port inside:

```text
server/app.js
```

Example:

```javascript
const PORT = 3000;
```

---

## Future Improvements

- JWT Authentication
- Password Hashing with bcrypt
- Better UI/UX
- Quiz Categories
- Scoreboard System
- Admin Dashboard
- Deployment Support

---

## License

This project is for educational purposes only.