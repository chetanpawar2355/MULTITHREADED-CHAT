# MULTITHREADED-CHAT

### Project Details:
- **Name:** Chetan Govind Pawar
- **Company:** CODTECH IT SOLUTIONS
- **ID:** CT08FBB
- **Domain:** Java Programming
- **Duration:** 20th December 2024 to 20th January 2025

---

### Overview:
This project implements a basic chat application using Java that allows multiple clients to communicate with each other via a server. The server handles incoming client connections and broadcasts messages to all connected clients.

---

### Features:
- **Server-side:**
  - Listens for incoming client connections on a specific port.
  - Accepts and processes messages from multiple clients simultaneously.
  - Broadcasts messages to all connected clients in real-time.
  
- **Client-side:**
  - Connects to the server and allows users to send and receive messages.
  - Displays messages received from the server in real-time.

---

### How to Run:

1. **Server Side:**
   - Open a terminal and navigate to the directory containing the `Server.java` file.
   - Compile the server program:
     ```bash
     javac Server.java
     ```
   - Run the server:
     ```bash
     java Server
     ```
   - The server will start and listen for incoming connections on port `12345`.

2. **Client Side:**
   - Open another terminal and navigate to the directory containing the `Client.java` file.
   - Compile the client program:
     ```bash
     javac Client.java
     ```
   - Run the client:
     ```bash
     java Client
     ```
   - The client will connect to the server at `localhost` and port `12345`.

3. **Multiple Clients:**
   - You can run multiple instances of the client to simulate communication between several clients through the server.

---

### Example Output:

#### Server Terminal:
```bash
![Screenshot 2025-01-19 160629](https://github.com/user-attachments/assets/28da8b1c-901a-4237-b35b-d047dc585893)
```

#### Client Terminal:
```bash
![Screenshot 2025-01-19 160759](https://github.com/user-attachments/assets/5664f026-5aea-4c33-b0ef-c2db7e525d3f)
```
