## Project Overview

The web chat application will have two main components:

1. **Client**:

   - Login form for users to enter a username and upload an avatar.
   - Chat interface where messages are displayed in real time.

2. **Server**:
   - Handles HTTP requests to upload images to Cloudinary and return image URLs.
   - Manages WebSocket connections to broadcast messages to all connected clients in real time.

## Features

- Real-time chat functionality using Socket.IO.
- User authentication through a simple login form.
- Image upload functionality for user avatars using Cloudinary API.
- Display of the last 10 messages to new users upon connection.

## Technologies Used

- **Frontend**:

  - React
  - Socket.IO-client

- **Backend**:
  - Node.js
  - Express
  - Socket.IO
  - MongoDB
  - Mongoose (for MongoDB interactions)
  - Cloudinary (for image storage)
