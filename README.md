# Chat App 💬 using WebSockets (Node.js, Express & Socket.io)

This chat application was developed using Node.js, Express, and Socket.io, leveraging WebSocket technology to enable real-time, bi-directional communication. The project integrates a custom front-end UI built with Flexbox, allowing for easy customization without relying on external libraries.

## Project Overview

This chat application establishes a full-duplex communication channel between the client and server, allowing instant data transmission in both directions. While WebSockets can be implemented natively, this project utilizes Socket.io, a popular library that simplifies WebSocket setup and provides a fallback to HTTP long polling when necessary, enhancing connectivity reliability.

### Features

* **Real-time Communication**:
  Messages are transmitted instantly between connected users, creating a responsive chat experience.
  
* **Socket.io Fallback**:
  Socket.io offers fallback support through XMLHttpRequests, ensuring stable connectivity even in limited network environments.
  
* **Responsive Front-End**:
  The UI uses Flexbox, enabling a flexible and customizable layout without external UI dependencies.

## Technology Stack and Resources

This project was built using:

* **Node.js**:
  The foundation for handling back-end operations and managing server communication.
  
* **Express**:
  A fast and minimalist web framework for Node.js to streamline server setup.
  
* **Socket.io**:
  Enables WebSocket connections, making real-time bidirectional communication easier to implement.

* **Frontend**:
  Custom, responsive UI crafted with Flexbox for ease of use and adaptability.
  
Additional resources referenced include Node.js documentation, Socket.io documentation, and JavaScript documentation for deeper insights into the technology stack and best practices.


## Setting Up the Project

Follow these steps to set up and run the chat application locally:

Step 1: Clone the Repository

```bash
git clone https://github.com/Sudeep458/Chat_Application
```
Step 2: Install Dependencies

```bash
cd chat-socket.io
npm install
```
Step 3: Start the Application (Development Mode)

```bash
npm run dev
```
Step 4: Run the Application in Production

```bash
npm start
```
