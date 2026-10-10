# ChatNest — Real-Time Chat Application

ChatNest is a real-time messaging application built with React, Node.js, and Socket.IO. It demonstrates how web technologies and WebSockets can be used to enable instant communication between users, with messages exchanged over persistent, bidirectional connections.

## Features

- **Real-Time Messaging:** Send and receive messages instantly using Socket.IO.
- **Interactive User Interface:** A React-based frontend for the chat experience.
- **WebSocket Communication:** Supports event-driven, bidirectional communication between the client and server.
- **Client–Server Architecture:** Separates the frontend interface from the backend communication layer.
- **Event-Based Messaging:** Uses Socket.IO events to handle real-time communication.

## Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend user interface |
| Node.js | JavaScript runtime |
| Socket.IO | Real-time, event-based communication |
| Express.js | Backend HTTP server, if configured in the project |
| JavaScript | Application logic |

## How It Works

1. The React frontend connects to the backend using Socket.IO.
2. The client emits messaging events to the server.
3. The server processes and relays events to the relevant connected clients.
4. Connected clients receive events and update the chat interface in real time.

This architecture illustrates the fundamentals of real-time, event-driven application development.

## Getting Started

### Prerequisites

Install the following before running the application:

- [Node.js](https://nodejs.org/)
- npm, which is included with Node.js

### Installation

Clone the repository and navigate to the project directory:

```bash
git clone <repository-url>
cd ChatNest
```

Install dependencies and start the application in each part of the project.

**Backend:**

```bash
cd server
npm install
npm start
```

**Frontend:**

Open another terminal:

```bash
cd client
npm install
npm start
```

Replace `server` and `client` with the actual directory names in your project, if they differ. Check each directory's `package.json` for the correct startup script; some React projects use `npm run dev` instead of `npm start`.

## Learning Outcomes

This project provides practical exposure to:

- Real-time communication using WebSockets and Socket.IO.
- Client–server communication and event-driven programming.
- Integrating a React frontend with a Node.js backend.
- Managing real-time events in a web application.




