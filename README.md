# MERN Stack Social Media App

A full-stack social media application built using the MERN stack (MongoDB, Express.js, React, and Node.js).

## Features

- User Authentication (Sign Up, Log In, Log Out)
- User Profiles
- Create, Read, Update, and Delete Posts
- Follow/Unfollow Users
- Like and Comment on Posts
- Responsive Design

## Tech Stack

- **Frontend:** React, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/iamrmittal/mern-social-media-app.git
    cd social-media-app
    ```

2. **Install dependencies for both backend and frontend:**

    ```bash
    # Install backend dependencies
    cd server
    npm install

    # Install frontend dependencies
    cd ../client
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the `backend` directory with the following variables:

    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. **Start the application:**

    ```bash
    # Start backend server
    cd backend
    npm start

    # Start frontend development server
    cd ../frontend
    npm start
    ```

5. **Open your browser:**

    Navigate to `http://localhost:3000` to see the application in action.

