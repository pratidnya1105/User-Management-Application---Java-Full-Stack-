# User Management Application (Full-Stack)

A complete, full-stack User Management application. This project features a modular architecture, splitting the user interface logic from the core business data operations.

---

## 📁 Repository Directory Structure


├── user-frontend/                 # React Frontend Application
│   ├── public/                    # Static assets and index.html
│   └── src/                       # Main application source code
│       ├── layout/                # Global layout components
│       ├── pages/                 # Page-level view components
│       ├── users/                 # User-specific functional modules
│       ├── App.js                 # Root component
│       └── index.js               # Entry point
│
└── userManagment/                 # Spring Boot Backend REST API
    ├── src/main/java/com/demo/    # Java backend source code
    │   ├── controller/            # API endpoints & HTTP request mapping
    │   ├── exception/             # Custom global error handling definitions
    │   ├── model/                 # Data entities & database schemas
    │   └── repository/            # Database access layer (Data interfaces)
    ├── pom.xml                    # Maven project configuration file
    └── README.md                  # Development notes


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
