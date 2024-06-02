# Simple-Chat

**Description:**
SimpleChat is a basic chat application built using Python's socket and threading libraries. It allows multiple clients to connect to a server and exchange messages in real-time.

**Features:**
- **Client-Server Architecture:** The server listens for incoming connections and handles multiple clients simultaneously.
- **Nickname Identification:** Clients choose a nickname which is used to identify them in the chat.
- **Message Broadcasting:** Messages sent by a client are broadcasted to all connected clients.
- **Threading for Concurrency:** Separate threads handle listening for new messages and sending messages for each client, ensuring smooth and responsive communication.

**Files:**
1. **client.py** - This file contains the code for the client-side operations:
    - Connects to the server.
    - Sends the chosen nickname to the server.
    - Receives and displays messages from the server.
    - Sends messages to the server.

2. **server.py** - This file contains the code for the server-side operations:
    - Listens for incoming client connections.
    - Handles client messages and broadcasts them to all connected clients.
    - Manages client connections and disconnections.
