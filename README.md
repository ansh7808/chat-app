# **Chat-App**
A real-time full-stack chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.IO for instant messaging. The app supports JWT-based user authentication, online user visibility, profile editing, and multimedia messaging.

## Features
-**User Authentication**
Sign up and login functionality using JWT tokens.
Passwords are securely hashed using bcrypt.
Protected routes and session management on both frontend and backend.

-**Real-Time Messaging (Socket.IO)**
Send and receive messages instantly without refreshing.
Real-time communication using WebSockets (via Socket.IO).
Chat interface updates live as messages are sent and received.

-**Online Users Display**
Left sidebar shows list of users who are currently online.
Sockets are used to track when users connect or disconnect.

-**Messaging Capabilities**
Send text and image messages in chat.
Messages are stored in MongoDB with metadata (sender, timestamp, type).
Image previews are shown within the chat window.

-**Chat History**
Persisted messages between users are stored and retrieved from MongoDB.
Chat opens with previous conversation loaded.

-**User Profile Management**
Right sidebar displays user’s profile, including:
Profile image
Bio
Media shared in chats
Users can edit their profile:
Upload new profile image
Update bio or personal details

# Project UI
![Image](https://github.com/user-attachments/assets/b59dd63a-e3dc-4ef9-bee1-769a37034295)
