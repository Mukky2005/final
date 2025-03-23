# TextSync - A Real-Time Collaborative Text Editor

A distributed text editor application that allows multiple users to edit text files in real-time. Built with React, Node.js, Socket.IO, and MongoDB.

## Features
- Real-time collaborative editing
- Rich text editing with Quill
- Automatic document saving
- Unique document URLs
- MongoDB for persistent storage

## Prerequisites
- Node.js
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Mukky2005/final.git
cd final
```

2. Install dependencies:
```bash
cd client && npm install
cd ../server && npm install
```

3. Create environment files:

For `server/.env`:
```
SERVER_ADDRESS=http://localhost
SERVER_PORT=3001
CLIENT_ADDRESS=http://localhost
CLIENT_PORT=3000
DATABASE_URI=mongodb://localhost:27017/textsync
```

For `client/.env`:
```
REACT_APP_SERVER_ADDRESS=http://localhost
REACT_APP_SERVER_PORT=3001
```

## Running the Application

1. Start the server:
```bash
cd server
npm start
```

2. Start the client (in a new terminal):
```bash
cd client
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

### Client
- React-based frontend
- Real-time updates using Socket.IO
- Rich text editing with Quill
- Automatic document saving

### Server
- Node.js backend
- Socket.IO for real-time communication
- MongoDB for document storage
- Document synchronization

## Technologies Used
- React
- Node.js
- Socket.IO
- MongoDB
- Quill Editor

## License
This project is licensed under the MIT License.
