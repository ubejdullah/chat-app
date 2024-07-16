# Chat Application | Chatify

## Overview
This is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application supports real-time messaging with emoji support, enhancing the chat experience.

## Features
- **Real-time Messaging:** Instant updates across all clients.
- **Emoji Support:** Use emojis to express yourself better.
- **User Authentication:** Secure login and registration system.
- **User Profiles:** Customize your profile with personal information.

## Technologies
- **Frontend:** React.js
- **Backend:** Express.js, Node.js
- **Database:** MongoDB
- **Real-time Communication:** Socket.io
- **Containerization:** Docker, Docker Compose

## Installation and Usage

### Installation

#### First Method
1. Clone the repository:
    ```shell
    git clone https://github.com/koolkishan/chat-app-react-nodejs
    cd chat-app-react-nodejs
    ```

2. Install the dependencies:
    ```shell
    cd server
    yarn
    cd ..
    cd public
    yarn
    ```
3. Start the development server.

   For Frontend:
    ```shell
    cd public
    yarn start
    ```
   
   For Backend (Open another terminal in the folder, and ensure MongoDB is running in the background):
    ```shell
    cd server
    yarn start
    ```
4. Done! Now open `localhost:3000` in your browser.

#### Second Method
- This method requires Docker and Docker Compose to be installed on your system.
- Make sure you are in the root of your project and run the following command:
    ```shell
    docker compose build --no-cache
    ```
- After the build is complete, run the containers:
    ```shell
    docker compose up
    ```
- Now open `localhost:3000` in your browser.
