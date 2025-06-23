# Freelancer_finder
 freelance platform that connects clients with skilled freelancers to post, bid, collaborate, and complete projects seamlessly. It ensures secure communication, efficient workflow, and real-time updates through a modern web architecture.

## 📌 Project Overview

SB Works transforms the way clients and freelancers connect. Clients can post detailed projects, review freelancer profiles, and select from multiple bids. Freelancers can showcase their skills, bid on jobs, collaborate through real-time chat, and submit work directly through the platform.

The platform ensures transparency and quality by enabling admin oversight and user feedback, fostering a trustworthy and efficient environment for remote collaboration.

## ✨ Key Features

- 🔐 **Authentication** – Secure login and role-based access for Clients, Freelancers, and Admins
- 📝 **Project Posting & Bidding** – Clients can post jobs; freelancers can browse and bid
- 💬 **Real-Time Messaging** – Integrated chat system using Socket.IO
- 📁 **Work Submission** – Freelancers can submit files securely through the platform
- 🌟 **Ratings & Reviews** – Clients can review freelancers post-project
- 🛡️ **Admin Panel** – Admins can manage users, monitor activity, and resolve issues
- 🔔 **Notifications** – Real-time alerts for new messages, bid status, and project updates

## 🧰 Tech Stack

### 💻 Frontend
- React.js
- Bootstrap / Material UI
- Axios
- Socket.IO (Client)

### 🌐 Backend
- Node.js
- Express.js
- Mongoose
- JWT Authentication
- Multer (for file uploads)
- Socket.IO (Server)

### 🗄️ Database
- MongoDB (with Mongoose ODM)

## 🧱 Architecture

This project follows a **client-server architecture**:

- **Frontend** handles UI and user interactions using React, styled with Bootstrap/Material UI. Axios is used for REST API calls, while Socket.IO powers real-time chat.
- **Backend** is built with Node.js and Express.js for handling API requests, authentication, and server-side logic.
- **Database** is managed with MongoDB, where Mongoose defines and interacts with schemas like users, projects, proposals, and messages.

## 👥 User Roles

| Role        | Capabilities |
|-------------|--------------|
| **Client** | Post projects, view bids, chat with freelancers, review work |
| **Freelancer** | Bid on projects, submit proposals, chat, submit work |
| **Admin** | Manage users/projects, oversee transactions, moderate content |


