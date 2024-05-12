# pro-c218 — Video Chat App

A small real-time chat application using Socket.IO for messaging and PeerJS for peer-to-peer video/audio.

## Features
- Real-time text messaging with Socket.IO.
- Peer-to-peer video/audio calls (PeerJS).
- Simple web UI (EJS + static assets hosted with Express).

## Tech Stack
- Node.js, Express, EJS
- Socket.IO, PeerJS, UUID

## Project Structure
```
├── server.js          # Express server + Socket.IO wiring
├── package.json
├── views/index.ejs    # chat page template
└── public/            # style.css, script.js
```

## Installation
```bash
npm install
```

## Usage
```bash
npm start        # or: node server.js
# Listening on http://localhost:3030 (or $PORT)
```
Open the app in two tabs/clients; send messages and make peer calls.