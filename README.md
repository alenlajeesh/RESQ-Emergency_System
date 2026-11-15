# 🚨 RESQ – AI-Powered Emergency Response System

**RESQ** is an emergency response and rescue assistance platform designed to make reporting emergencies, coordinating responders, and managing rescue operations easier and more efficient.

The platform connects citizens, emergency responders, and administrators through a centralized system, helping emergency reports reach the appropriate people and allowing rescue operations to be monitored and managed.

## 🌟 Features

### 👤 Citizen

- Report emergencies through the platform.
- Share location information using GPS.
- Attach images and audio to emergency reports.
- View incident information and updates.
- Track the progress of reported emergencies.

### 🚑 Emergency Responder

- View reported emergency incidents.
- View incident locations on an interactive map.
- Share GPS location information.
- Manage availability and accept emergency assignments.
- Update the status of ongoing rescue operations.

### 🛡️ Admin Dashboard

- Monitor emergency incidents.
- View platform statistics and analytics.
- Manage responders and emergency assignments.
- Monitor incident statuses.
- Coordinate emergency response activities.

### 🤖 AI Integration

RESQ is designed with AI-assisted emergency response capabilities.

## 🛠️ Technology Stack

| Component               | Technology                   |
| ----------------------- | ---------------------------- |
| Frontend                | React.js                     |
| Backend                 | Node.js, Express.js          |
| Database                | MongoDB                      |
| Location services       | GPS / Geolocation            |

## 📂 Project Structure

```text
RESQ-Emergency-System/
│
├── resq-frontend/
│   ├── public/
│   ├── src/
│   ├── .env.example
│   ├── .gitignore
│   ├── .oxlintrc.json
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   └── vite.config.js
│
├── resq-backend/
│   ├── src/
│   ├── .env.example
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   └── server.js
│
├── resq-ml/
│   ├── data/
│   ├── models/
│   ├── .gitignore
│   ├── augment.py
│   ├── command.txt
│   ├── requirements.txt
│   ├── safety_net.py
│   ├── serve.py
│   ├── train.py
│   └── try_it.py
│
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB
- Git

### 1. Clone the repository
```
git clone https://github.com/YOUR_USERNAME/RESQ-Emergency-System.git
cd RESQ-Emergency-System
```

### 2. Set up the backend
```
cd resq-backend
npm install
```

Create a `.env` file in the backend directory and configure the required environment variables.
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Add any other environment variables required by your implementation.

Start the backend:
```
npm start
```

### 3. Set up the frontend

Open another terminal:
```
cd resq-frontend
npm install
npm start
```

The application should now be accessible through the local development address shown by your frontend development server.

## 🎯 Project Objectives

- Make emergency reporting more accessible.
- Improve communication between citizens and emergency responders.
- Help responders locate and manage emergency incidents.
- Provide administrators with tools to coordinate rescue operations.
- Explore the use of AI to support emergency response activities.


## 🔮 Future Improvements

- Expand AI-assisted emergency analysis and support.
- Improve emergency location accuracy.
- Enhance real-time communication.
- Improve responder coordination and resource management.
- Develop mobile application support.

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

---

**RESQ – Connecting People, Responders, and Technology When Every Second Matters.**
