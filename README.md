# MERN Chat App

This repository contains a full-stack chat application built using the MERN stack (MongoDB, Express.js, React, Node.js). The chat application is designed with various features to enhance user experience, including real-time updates using WebSockets, online status indicators, file uploads/attachments, and auto-scrolling, among others.

## Features

- **Real-time Communication**: Utilizes WebSockets for instant messaging and updates.
- **Online Indicator**: Shows when users are online/offline.
- **File Uploads/Attachments**: Allows users to share files during chats.
- **Auto-Scrolling**: Automatically scrolls to the latest message in active chats.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Installation

To run this application locally, you need to have Node.js and MongoDB installed on your machine.

1. Clone this repository:

   ```bash
   git clone https://github.com/KrlosDev/mern-chat.git
   ```
2. Install dependencies:

   ```
   cd client
   npm install
   ```
      ```
   cd api
   npm install
   ```
### Set up environment variables:

1. Create a .env file in the root directory and provide the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000  # or any other port you want to use for the server
   ```
2. Start the client:
   ```
   npm run dev
   ```
3. Start the server:
   ```
   npm start
   ```
# Contributing
Contributions are welcome! Please fork this repository and create a pull request with your improvements.
