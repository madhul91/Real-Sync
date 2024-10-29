# Real-Sync
Welcome to the Real-Time Chat Application! This project is built using the MERN stack and leverages Socket.io for real-time capabilities, alongside Redux Toolkit for state management. The application offers features like real-time messaging, user online status, user search functionality, and more.


# Project Overview
This application is a real-time messaging platform that enables authenticated users to send messages,  receive notifications, and search for other users. The project demonstrates the use of React for building a responsive UI, Node.js and Express.js for handling the server-side logic, MongoDB for data storage, and Socket.io for enabling real-time interactions.

# Features
Real-Time Messaging: Send and receive messages instantly with the help of Socket.io. 

User Authentication: Authenticate using JWT 

Online Status: View online/offline status of users in real-time.

Search for Other Users: Find and connect with other users through a search bar.

Redux Toolkit for State Management: Efficient state handling and scalable architecture.

Responsive UI: Built with Tailwind CSS for a clean and responsive design.

Notifications: Receive alerts for new messages and user activities.

Secure Data Transmission: Protect user data and conversations with robust authentication and security practices.
# Tech Stack
Frontend:
React.js
Redux Toolkit
Tailwind CSS

Backend:
Node.js
Express.js
Socket.io

Database:
MongoDB
Authentication:

JWT (JSON Web Tokens)

# Getting Started
To get a local copy of this project up and running, follow these simple steps.

Prerequisites
Node.js (v14 or higher)
MongoDB (Local or Cloud-based)

Setup Instructions
1. Clone the Repository
bash
Copy code
git clone https://github.com/your-username/real-time-chat-app.git
cd real-time-chat-app
2. Install Dependencies
For both the server and client, install the dependencies:

bash
Copy code
# Server setup
cd server
npm install

# Client setup
cd ../client

npm install

3. Environment Variables
Create a .env file in the server directory with the following variables:

makefile
Copy code
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key

4. Run the Application
Start the server and client concurrently:

bash
Copy code
# Server (in /server directory)
npm run dev

# Client (in /client directory)
npm start

Available Scripts
In the server directory:

npm run dev - Runs the server in development mode using nodemon.
npm start - Runs the server in production mode.
In the client directory:

npm start - Runs the React application in development mode.
npm run build - Builds the app for production.
Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project.
Create your Feature Branch (git checkout -b feature/feature-name).
Commit your Changes (git commit -m 'Add some feature').
Push to the Branch (git push origin feature/feature-name).
Open a Pull Request.
License
Distributed under the MIT License. See LICENSE for more information.
