
---

# Java Chat Application

A simple client-server chat application built in Java, featuring a GUI for real-time messaging.

## Features
- Real-time messaging between multiple clients.
- User-friendly GUI with message timestamps.
- Supports multiple clients connected to a single server.

## Files
- **ChatServer.java**: Handles client connections and message broadcasting.
- **ChatClient.java**: Manages client-server communication.
- **ChatClientGUI.java**: Provides a graphical user interface for the chat client.

## How to Run

1. **Start the Server**:
   ```bash
   javac ChatServer.java
   java ChatServer
   ```
   - The server will run on port `5000` by default.

2. **Start a Client**:
   ```bash
   javac ChatClientGUI.java
   java ChatClientGUI
   ```
   - Enter a username when prompted.

3. **Interact**:
   - Multiple clients can connect to the server for messaging.

## Prerequisites
- Java Development Kit (JDK) installed.
- Basic understanding of Java programming.

## Example

1. Start the server:
   ```bash
   java ChatServer
   ```
2. Open the client and connect:
   ```bash
   java ChatClientGUI
   ```

3. Chat in real-time with other connected clients.

---
