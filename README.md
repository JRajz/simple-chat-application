# Simple Chat Application in Node.js with Socket.IO

This is a simple chat application built using Node.js and Socket.IO. It includes both the server-side and client-side code to enable real-time communication between users.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone git@github.com:JRajz/simple-chat-application.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd simple-chat-application
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

## Usage

1. **Start the server:**

   ```bash
   npm start
   ```

   This will start the server on `http://localhost:3000`.

2. **Open your web browser and go to `http://localhost:3000`.**

3. **Enter your username and room, start chatting with others in real-time!**

## Socket.IO Events

- `connection`: Triggered when a user is connected.
- `joinRoom`: Use this event to join a particular room.
- `message`: Send a message to the room joined by the user.
- `roomUsers`: Retrieve a list of users in a particular room.
- `disconnect`: Triggered when a user leaves the chat.
- `chatMessage`: Listen for this event to receive a particular message.

## Project Structure

- `index.js`: The main server file that sets up the Socket.IO server and handles connections.
- `public/index.html`: The HTML file containing the front-end code for the chat application.
- `public/css/.css`: CSS file for styling the chat interface.
- `public/js/main.js`: JavaScript file containing the client-side code for interacting with the Socket.IO server.

## Dependencies

- [express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js. (`^4.18.2`)
- [moment](https://www.npmjs.com/package/moment): Parse, validate, manipulate, and display dates in JavaScript. (`^2.29.4`)
- [path](https://www.npmjs.com/package/path): Provides utilities for working with file and directory paths. (`^0.12.7`)
- [socket.io](https://www.npmjs.com/package/socket.io): Enables real-time, bidirectional, and event-based communication. (`^4.7.2`)

## Contributing

Feel free to contribute to the development of this chat application. You can create issues, submit pull requests, or provide feedback.

Happy chatting! 🚀
