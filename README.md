## Giggle Backend 🎵

RESTful API and real-time messaging server for the Giggle mobile app - connecting gig-goers through free ticket sharing.

Built by isLoading team for Northcoders bootcamp final project.

🔗 Frontend Repository: Giggle FE

About
Backend API for a community-driven ticket sharing platform. Handles user authentication, event management, ticket listings, and real-time messaging - all focused on free ticket sharing with no reselling.

Key Features

🎫 Event & Ticket API - Browse events, manage ticket listings, Ticketmaster integration

🔐 Secure Authentication - JWT tokens, bcrypt password hashing

👤 User Profiles - Gig preferences, compatibility matching

💬 Real-time Messaging - Socket.IO powered chat system

🗄️ MongoDB Database - Flexible schema with Mongoose ODM


Quick Start

Prerequisites:Node.js (v14+), MongoDB

Clone and install

git clone https://github.com/Andipascale7/giggle-be.git
cd giggle-be
npm install

Environment setup:

- Create .env.development
  MONGO_DEV=mongodb://localhost:27017/giggle

- Create .env.test
 MONGO_DEV=mongodb://localhost:27017/giggle

  Start servers:
  Main API server  --> npm run dev

  

Tech Stack

Express.js + TypeScript - API development
MongoDB + Mongoose - Database and ODM
Socket.IO - Real-time messaging
Jest - Testing

