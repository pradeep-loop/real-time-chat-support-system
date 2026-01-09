Real-Time Chat Application 🚀
📌 Project Overview

This project is a Real-Time Chat Application developed using Python Flask and Flask-SocketIO. The main goal of this project is to enable instant one-to-one communication between users with features such as online/offline status tracking, file sharing, and a user-friendly chat interface.

The application demonstrates how real-time communication works using WebSockets and how backend logic, frontend UI, and database integration come together in a full-stack project.

🎯 Objectives of the Project

To understand and implement real-time communication using Socket.IO

To build a full-stack application using Python Flask

To handle live user connections and message delivery

To provide a simple yet functional chat UI

To store and manage chat-related data using MongoDB

🧠 Key Features

✅ Real-time one-to-one chat

✅ Instant message delivery using Socket.IO

✅ Online / Offline user status tracking

✅ File upload and sharing support

✅ Emoji-enabled chat interface 😄

✅ Clean and responsive UI

✅ Lightweight and easy-to-run architecture

🛠️ Technologies Used
Backend

Python

Flask

Flask-SocketIO

Frontend

HTML

CSS

JavaScript (inline)

Database

MongoDB (running on localhost)

Other Tools

Socket.IO (for WebSocket-based communication)

📂 Project Structure
CHAT/
 └── pradeep.py
File Explanation

pradeep.py

Main application file

Contains backend logic, Socket.IO events, and frontend HTML/CSS/JS

This is a single-file full-stack project, making it easy to understand and deploy.

⚙️ How the Project Works (Flow Explanation)

The Flask server starts and listens on port 5000

Users open the application in a browser

Socket.IO establishes a persistent WebSocket connection

When a user sends a message:

The message is emitted through Socket.IO

The server receives and forwards it instantly

The receiver sees the message in real time

User connection and disconnection events update online/offline status

Uploaded files are validated and shared through the chat interface

▶️ How to Run the Project
Prerequisites

Python 3.x installed

MongoDB installed and running

Required Python Packages
flask
flask-socketio
pymongo
Steps to Run
python pradeep.py
Access the Application

Open your browser and go to:

http://localhost:5000
🗄️ Database Details

Database: MongoDB

Host: localhost

Port: 27017

MongoDB is used to store:

User-related information

Chat-related data

🔐 Validations & Limitations

File upload size is limited (maximum 8MB)

Basic validations are implemented for stability

Designed for learning and demonstration purposes

🌱 Future Enhancements (Optional)

Group chat support

Authentication and login system

Message history persistence

Improved UI/UX

Deployment on cloud platforms

🎤 Interview Explanation (Quick Summary)

This project is a real-time chat application built using Python Flask and Socket.IO. It supports instant messaging, online status tracking, and file sharing. MongoDB is used for backend data storage, and WebSockets ensure low-latency communication.

👨‍💻 Author

L Pradeep Raj

📜 License

This project is created for educational and learning purposes.

✨ Thank you for checking out this project!
