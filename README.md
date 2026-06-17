# User Management Application (Full-Stack)

A complete, full-stack User Management application. This project features a modular architecture, splitting the user interface logic from the core business data operations.

---

## 📁 Repository Directory Structure

<img width="797" height="605" alt="image" src="https://github.com/user-attachments/assets/29c7985a-df9d-4349-a34d-b5e5d23c6987" />


---

## 💻 Frontend Setup (React)

### Prerequisites
Make sure you have [Node.js](https://nodejs.org) installed.

### Steps to Run Locally
1. Navigate to the frontend directory:
   ```bash
   cd user-frontend
   ```
2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Start the local development web server:
   ```bash
   npm start
   ```
The frontend application will load in your browser at `http://localhost:3000`.

---

## ☕ Backend Setup (Spring Boot)

### Prerequisites
Make sure you have Java **JDK 24** installed on your system.

### Steps to Run Locally
1. Navigate to the backend directory:
   ```bash
   cd userManagment
   ```
2. Build the project artifacts using the Maven wrapper:
   ```bash
   # On Windows:
   mvnw.cmd clean install


3. Boot up the backend server:
   ```bash
   # On Windows:
   mvnw.cmd spring-boot:run

  
The server will boot up and listen for requests at `http://localhost:8080`.

---

## 🔌 Primary REST API Endpoints
* `GET /api/users` — Retrieve all users
* `GET /api/users/{id}` — Retrieve details of a specific user
* `POST /api/users` — Add a new user profile
* `PUT /api/users/{id}` — Modify an existing user profile
* `DELETE /api/users/{id}` — Erase a user profile

## Output of the project

<img width="1197" height="897" alt="image" src="https://github.com/user-attachments/assets/d79c0179-2387-4a1a-bd75-00c38b2446cd" />

