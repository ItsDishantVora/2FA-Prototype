# Two-Factor Authentication Prototype

This project serves as a prototype for testing a basic user authentication system with two-factor authentication (2FA). It is developed using the MERN stack and allows users to sign up, log in, verify their phone number via 2FA, and access a dashboard. This system is part of an experimental setup to understand the nuances of implementing 2FA in web applications.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following software installed:
- Node.js
- npm (Node Package Manager)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://your-repository-url.git
   cd your-project-folder
   ```

2. **Install dependencies:**
   ```bash
   # Install dependencies for server
   cd server
   npm install

   # Install dependencies for client
   cd ../client
   npm install
   ```

3. **Start the server:**
   ```bash
   # Navigate back to the server folder if you are not already there
   cd ../server
   npm start
   ```

4. **Run the client:**
   ```bash
   # In a new terminal window, navigate to the client folder
   cd ../client
   npm start
   ```

   This will run the React application in development mode.\
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Usage

- **Sign Up:** Users can sign up by providing their email, password, username, and phone number.
- **Phone Verification:** After registration, users need to verify their phone number using a code sent via SMS.
- **Log In:** Users can log in using their email and password.
- **Dashboard:** Upon successful login, users will navigate to the dashboard where they can sign out.

## Built With

- [React.js](https://reactjs.org/) - The web framework used
- [Node.js](https://nodejs.org/) - Runtime environment
- [Express.js](https://expressjs.com/) - The server framework used
- [MongoDB](https://www.mongodb.com/) - Database system (assumed as part of MERN stack)

## Team Members

- Dishant Vora
- Niyati Mittal
- Carlos Schenone
- Lu Wang
- Jeri Rao

## Acknowledgments

This project is designed to test the functionalities and robustness of 2FA in a controlled development environment. It is intended to provide insights and learnings that could be applied to larger scale applications.
