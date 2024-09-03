# STUDENT MANAGEMENT SYSTEM

Welcome to the Student Management System, a robust solution crafted to streamline educational institution operations, optimize student management, and facilitate effective communication among stakeholders. Leveraging the power of the MERN stack (MongoDB, Express.js, React.js, Node.js), this web-based application offers a multitude of features designed to enhance administrative efficiency and academic excellence.

## About

The Student Management System provides a centralized platform for managing students, faculty, classes, and subjects efficiently. It empowers users with specialized functionalities and access permissions tailored to their roles, ensuring smooth workflow and seamless collaboration.

### Features

- **User Roles:** Three distinct user roles—Admin, Teacher, and Student—with specialized functionalities and access permissions.
- **Admin Dashboard:** Comprehensive dashboard for managing students, teachers, classes and subjects.
- **Attendance Tracking:** Enables teachers to mark attendance and view attendance history.
- **Data Visualization:** Interactive charts and graphs offer students insights into their academic performance, fostering self-awareness and continuous improvement.
- **Notice and Complaints:** Dedicated section for posting notices and complaints, facilitating effective communication between students, teachers, and administrators

### Technologies Used

- **Frontend:** 
  - React.js
  - Material UI
  - Redux

- **Backend:** 
  - Node.js
  - Express.js

- **Database:** 
  - MongoDB

## Installation

### Prerequisites

Before getting started, ensure you have the following prerequisites installed on your system:

- [Node.js](https://nodejs.org/en/) (including npm)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation Steps

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/vatsalya-vyas/Student-Management-System.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd Student-Management-System
    ```

#### Backend Setup

1. **Navigate to the Backend Directory:**
    ```bash
    cd Backend
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**
    Create a `.env` file in the backend directory and add your MongoDB connection string:
    ```plaintext
    MONGO_URL=your_mongodb_connection_string
    ```

4. **Start the Backend Server:**
    ```bash
    npm start
    ```

#### Frontend Setup

1. **Navigate to the Frontend Directory:**
    ```bash
    cd Frontend
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**
    Create a `.env` file in the frontend directory and specify the base URL for the backend server:
    ```plaintext
    REACT_APP_BASE_URL=http://localhost:5000
    ```

4. **Start the Frontend Application:**
    ```bash
    npm start
    ```

Once the frontend server starts, your default web browser should open automatically to `http://localhost:3000`, where you can access and interact with the Student Management System.
