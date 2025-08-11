## Giggle Backend 🎵 Group Project

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


- **RESTful API** built with Express.js and TypeScript
- **MongoDB** database with Mongoose ODM
- **Socket.IO** for real-time communication (separate port)
- **Ticketmaster Discovery API** for event data


### Testing
- **Jest** for unit testing



### Key API Endpoints
- `GET /events` - Fetch upcoming events
- `POST /tickets` - Upload new ticket listings  
- `GET /tickets/:eventId` - Get tickets for specific event
- `GET /chats` - Fetch user's active conversations
- `GET /chats/:id` - Get chat history for specific conversation


## 👥 The Team - isLoading

- [**Andi Pascale**](https://www.linkedin.com/in/andipascale/)
- [**Bethany White**](https://www.linkedin.com/in/bethpwhite/) 
- [**David Potter**](https://www.linkedin.com/in/dg-potter013/)
- [**Leah Stone**](https://www.linkedin.com/in/leah-s-ba9004130/) 
- [**Uzo Ugochukwu**](https://github.com/uzougochukwu)
