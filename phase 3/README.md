---

# Multi-Client Chat Server with Nicknames

This project implements a simple multi-client chat server where clients can connect, send messages, and receive messages from other clients. Each client is required to enter a unique nickname upon joining. The server handles multiple clients simultaneously using threads.

---

## Getting Started

### Prerequisites

This project uses the following built-in Python modules:
- `socket` for network communication.
- `threading` to handle multiple clients concurrently.

### Running the Application

1. **Start the Server**: 
   - Run the server script (`server.py`). The server will begin listening for incoming client connections.

2. **Start the Clients**:
   - Run one or more client scripts (`client.py`). Each client will connect to the server and provide a nickname.

3. **Send Messages**:
   - Clients can send messages, which will be broadcast to all connected clients.

4. **Exit the Chat**:
   - Clients can leave the chat by typing `/exit`, and the server will notify others of the departure.

> **Note**: Clients must enter a username before sending messages. New clients will be prompted to provide a username when they connect.

---

## Features and Summary

- **Nickname Requirement**: Clients are prompted to provide a unique nickname when they join.
- **Real-Time Communication**: Messages sent by one client are broadcast to all connected clients.
- **Graceful Exit**: Clients can leave by typing `/exit`, and the server will notify others.
- **Multi-Client Support**: The server uses threading to handle multiple clients concurrently.

This chat server demonstrates the power of socket programming and multi-threading in Python, providing a basic yet effective foundation for building more complex communication systems.