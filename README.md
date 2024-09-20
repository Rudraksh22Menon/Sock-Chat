# Sock Chat: Client-Server Chat Application in C

**Sock Chat** is a basic chat application built using **C** and socket programming, featuring a **server** that manages client connections and a **client** for real-time messaging.

## Features
- **Real-time Communication**: Clients can send and receive messages instantly.
- **Socket Programming in C**: Utilizes the `socket` API for network communication.
- **Multiple Clients**: Server handles multiple client connections concurrently.

## How It Works
- The **server** accepts incoming client connections and manages them in parallel.
- **Clients** connect to the server and can exchange messages in a shared chat room.
- The server ensures all messages are broadcasted to every connected client.

## Technologies Used
- **C Programming Language**: Core implementation of both client and server.
- **Sockets**: For establishing client-server communication.
- **Multi-threading (optional)**: To handle multiple clients at once on the server side.

## Future Enhancements
- **GUI Integration** using libraries like GTK or ncurses.
- **Encryption** to secure message transfers.
- **Private Messaging** functionality.
