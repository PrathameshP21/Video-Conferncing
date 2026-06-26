# live Demo
https://krunex-frontend.onrender.com

# Video Conference App

A real-time 1-on-1 video calling app with chat, built using WebRTC for peer-to-peer video/audio and Socket.io for signaling.

## Features

- User authentication (login/signup)
- Guest join via meeting code (no login required)
- Create or join meetings using a unique meeting code
- Real-time 1-on-1 video & audio calling (WebRTC)
- Mute/unmute audio, end call, screen sharing
- Real-time in-call chat
- Meeting history for logged-in users

## Tech Stack

**Frontend:** React, Socket.io-client, WebRTC APIs
**Backend:** Node.js, Express, Socket.io, MongoDB (Mongoose)
**Auth:** JWT, bcrypt

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB connection string

### Backend Setup
```bash
cd backend
npm install
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### Environment Variables
Create a `.env` file in the `backend` folder:
```
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Live Demo

https://krunex-frontend.onrender.com

## License

ISC
