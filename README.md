# **React-Express WebSocket File Sharing**

A lightweight and efficient file-sharing application built with **React**, **Express**, and **WebSocket**. This project enables real-time file transfer between users over WebSocket, ensuring seamless and fast communication.

## 🚀 **Features**

- **Real-time File Sharing**: Share files instantly between users without page reloads.
- **WebSocket Communication**: Ensures low-latency, full-duplex communication.
- **Modular Design**:
  - **Client**: Built with React for a dynamic and responsive interface.
  - **Server**: Powered by Express for a robust backend.
- **Cross-Platform Compatibility**: Works across all modern browsers and platforms.

## 🛠️ **Technologies Used**

- **React**: Frontend framework for building interactive user interfaces.
- **Express**: Lightweight Node.js framework for backend services.
- **WebSocket**: Protocol for real-time, two-way communication.
- **Node.js**: JavaScript runtime environment for the server.

## 📂 **Project Structure**

- **client/**: Contains the React application for the frontend interface.
- **server/**: Includes the Express server for managing WebSocket connections and file sharing.

## 💻 **Getting Started**

### Prerequisites
- Node.js installed on your machine.
- Basic knowledge of React and Express.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yashChouriya/react-express-ws-file-share.git
   cd react-express-ws-file-share
   ```

2. Install dependencies for both client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Start the server:
   ```bash
   cd server
   npm start
   ```

4. Start the client:
   ```bash
   cd client
   npm start
   ```

5. Open the app in your browser at `http://localhost:3000`.

## 📖 **How It Works**

1. Users upload files through the client interface.
2. The files are sent to the server via WebSocket for processing and sharing.
3. Recipients can download the files in real-time.

## 🤝 **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request.

## 📄 **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.
