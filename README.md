**Multiple Chat System**
<br>
This project is a real-time multiple chat system built using Java socket programming. <br>
It allows multiple clients to connect to a server and communicate with each other seamlessly. <br>
The server manages connections and broadcasts messages to all active clients, enabling group chat functionality. <br>
The system demonstrates fundamental networking concepts such as socket communication, multithreading, and client-server architecture. <br> **<br>

**Key Features** <br> <br>
Multi-client Support: The system allows multiple users to connect and interact concurrently without interference.<br>
Broadcast Messaging: Messages sent by one client are automatically relayed to all other connected clients by the server.<br>
Scalable Design: The server can handle numerous simultaneous connections, demonstrating efficient use of Java threads. <br>
Simple Command-Line Interface (CLI): Both the client and server run on the terminal, ensuring lightweight execution and easy debugging. <br> <br> <br>

**The server** is implemented using the ServerSocket class, listening for incoming client connections. Each client connection is managed on a separate thread, ensuring simultaneous communication without blocking the main server process.
**Clients** use the Socket class to establish a connection with the server. They can send messages to the server, which are then broadcast to all other connected clients.
A simple text-based protocol is used for sending and receiving messages, making the system easy to extend. <br>

This is a practical demonstration of Java's networking and threading capabilities, making it a great tool for understanding the fundamentals of client-server communication.
