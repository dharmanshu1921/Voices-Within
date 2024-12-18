# Voices Within 💜🧠

## Overview

Voices Within is a compassionate mental health awareness website designed to create a safe and supportive online space for individuals to explore and nurture their mental well-being. The platform offers resources, support, and a welcoming environment for those seeking mental health information and connection.

## Features

- 🔐 User Authentication (Register, Login, Logout)
- 💬 Safe and Supportive Platform
- 🌈 Intuitive User Interface
- 📱 Responsive Design

## Technology Stack

### Client-Side
- ReactJS
- CSS3
- React Context API for State Management
- Reactjs-popup

### Server-Side
- Node.js
- Express.js
- MongoDB
- Mongoose

## Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB

## Local Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/voices-within.git
cd voices-within
```

### 2. Install Dependencies

#### Server-Side
```bash
cd server
npm install mongoose cors express nodemon axios
```

#### Client-Side
```bash
cd client
npm install reactjs-popup
```

### 3. Set Up MongoDB
- Download and install MongoDB: [MongoDB Installation Guide](https://www.mongodb.com/docs/manual/installation/)
- Ensure MongoDB Compass is installed

### 4. Running the Application

#### Start Server
```bash
cd server
nodemon index.js
```

#### Start Client
```bash
cd client
npm start
```
###5. Database Connection

Log in to MongoDB Atlas
Navigate to your cluster
Click "Connect" and choose your connection method
Use the generated connection string in your server configuration
Whitelist your IP address in the Atlas network access settings

## Authentication Flow
- Registration
- Login
- Logout

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
