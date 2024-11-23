# Todo List Application

A full-stack Todo List application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This app allows users to create, update, delete, and manage tasks effectively.

---

## Features
- **Frontend (Client):** A React-based user interface to interact with tasks.
- **Backend (Admin):** A Node.js/Express server handling CRUD operations with MongoDB as the database.
- Responsive and interactive user experience.

---

## Technologies Used
- **Frontend:** React, CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Other Tools:** npm, Vite (for development)

---

## Project Structure
/Server 
- Models
   - Todo.js - Mongoose schema for tasks
- index.js - Backend entry point

/todolist /src 
- App.jsx - Main React component
- Home.jsx - Task display page
- Create.jsx - Task creation page

/public 
   - index.html - React's entry point HTML
- package.json - React dependencies

---

## How to Run the Application

### Prerequisites
1. **Node.js** and **npm** installed.
2. **MongoDB** running locally or accessible via a connection string.

### Steps to Run the Application

#### Backend (Admin)
1. Navigate to the `Server` folder:
   ```bash
   cd Server


2. Install backend dependencies:
   ```bash
   npm install
3. Start the backend server:
   ```bash
   node index.js
4. The backend will run at `http://localhost:5000` (or the port configured in your `index.js`).

---

#### Frontend (Client)

1. Navigate to the todolist folder:
   ```bash
   cd todolist
2. Install frontend dependencies:
   ```bash
   npm install
3. Start the React app:
   ```bash
   npm start
4. The frontend will be available at `http://localhost:3000`.

---

## Additional Information

- **Languages Used**: JavaScript, JSX, CSS
- **Database**: MongoDB (using Mongoose for schema modeling)
- **Server**: Node.js with Express.js
- **Frontend Library**: React.js

---

## Screenshots

###To-Do List interface

![image](https://github.com/user-attachments/assets/af0a2bd1-2f23-4b68-b76e-d9b8a258de4c)


###MongoDBCompass

![image](https://github.com/user-attachments/assets/ac8c5459-7c6a-43ec-8146-ea06ae38d469)

---
