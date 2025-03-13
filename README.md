# Student Guidance Platform

## Overview
Student Guidance Platform is a MERN-based application designed to assist students in choosing their career paths. The platform is integrated with **Razorpay (Test Mode)** to simulate payment processing and features an **e-commerce-style front page** for an intuitive user experience.

## Features
- **Career Guidance System**: Provides personalized career recommendations.
- **E-commerce UI**: A visually appealing stock front page.
- **Razorpay Integration**: Supports test mode payments.
- **MongoDB Database**: Stores student data and recommendations.
- **MERN Stack Implementation**: Built using **MongoDB, Express, React, and Node.js**.

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/sairam-mekala/Student-Guidance-Platform.git
cd Student-Guidance-Platform
```

### 2. Database Setup (MongoDB)
1. Open **MongoDB Compass**.
2. Create a database named **`mernproject`**.
3. From the **resources** folder, upload all CSV files into their respective schemas.

### 3. Backend Setup
```bash
cd server
npm install
npm start
```

### 4. Frontend Setup
In a new terminal, run:
```bash
cd client
npm install
npm run dev
```

### 5. Access the Application
Once the frontend and backend are running, open the application in your browser:
```
http://localhost:3000
```

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via MongoDB Compass)
- **Payment Gateway**: Razorpay (Test Mode)

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m 'Added new feature'`
4. Push the changes: `git push origin feature-branch`
5. Open a pull request.
