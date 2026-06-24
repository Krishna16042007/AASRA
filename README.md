# AASRA – NGO Support & Complaint Management System

## Overview
AASRA is a web-based platform that connects citizens with NGOs and support organizations. It enables users to submit complaints, request assistance, track case progress, and access support services through a single, user-friendly system.

## Problem Statement
People often struggle to find the right organization when they need social, educational, financial, or emergency assistance. Existing systems are fragmented, lack transparency, and make it difficult to track requests.

AASRA addresses these challenges by providing a centralized platform for communication and support management.

## Features

### User Features
- User Registration & Login
- Submit Complaints and Support Requests
- Track Complaint Status
- Search NGOs by Category
- View NGO Details
- Update Profile Information
- Receive Notifications

### NGO Features
- NGO Registration
- View Assigned Cases
- Manage Complaints
- Update Complaint Status
- Respond to User Requests

### Admin Features
- Dashboard Analytics
- User Management
- NGO Verification
- Complaint Monitoring
- Report Generation

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Tools
- Git
- GitHub
- VS Code

## Project Structure

AASRA/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── complaint.html
│   ├── profile.html
│   ├── css/
│   └── js/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── config/
│
├── database/
├── screenshots/
├── README.md
└── package.json

## Installation

### Clone Repository
git clone https://github.com/your-username/AASRA.git

### Navigate to Project
cd AASRA

### Install Dependencies
npm install

### Configure Environment Variables

Create a .env file and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### Run Application
npm start

Server will run at:
http://localhost:5000

## Database Schema

### Users
- name
- email
- password
- role

### NGOs
- ngoName
- category
- address
- contact

### Complaints
- title
- description
- category
- status
- userId
- ngoId
- createdAt

## Workflow

User Registration
↓
Submit Complaint
↓
Admin Review
↓
NGO Assignment
↓
Action Taken
↓
Status Update
↓
Issue Resolved

## Future Enhancements

- AI-Based Complaint Classification
- Real-Time Chat Support
- Email & SMS Notifications
- Mobile Application
- Multi-Language Support
- Emergency SOS System
- NGO Recommendation Engine

## Contributors

- Krishna Singh
- Team Members

## License

This project is developed for educational and social impact purposes.

## Vision

"Empowering citizens by providing a transparent, accessible, and efficient platform to connect with NGOs and receive timely assistance."
