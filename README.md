# OTP Authentication System

This repository contains the code for implementing a complete OTP (One-Time Password) authentication system using the MERN (MongoDB, Express.js, React.js, Node.js) stack. With this system, users can register for an account, verify their identity using OTP sent to their mobile number or email, and securely authenticate themselves.

## Features

- User Registration
- OTP Verification
- User Authentication
- Change Password
- Password Encryption
- Token-Based Authentication
- Responsive UI

## Tech Stack

- Frontend:
  - React.js
  - React Router
  - Axios
  - Material-UI

- Backend:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JSON Web Tokens (JWT)
  - Nodemailer (for email OTP)

## Setup Instructions

1. **Clone the Repository**: Use `git clone` to clone this repository to your local machine.
   ```bash
   git clone https://github.com/naumanch969/otp-authentication.git
   ```

2. **Backend Setup**:
   - Navigate to the `backend` directory:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Configure environment variables:
     - Create a `.env` file based on the provided `.env.example` template.
     - Update the environment variables with your MongoDB connection URI, JWT secret key, and Twilio API credentials (if using SMS OTP).
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Frontend Setup**:
   - Navigate to the `frontend` directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the frontend development server:
     ```bash
     npm start
     ```

4. **Access the Application**:
   - Once both the backend and frontend servers are running, you can access the application at `http://localhost:3000` in your web browser.
     
---

Feel free to explore, test, and customize this OTP authentication system according to your requirements. If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. 

Happy coding! 🚀
