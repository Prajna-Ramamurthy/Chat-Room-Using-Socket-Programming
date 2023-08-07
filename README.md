# Chat-Room-Using-Socket-Programming
Computer Networks Assignment

Creating a chat room using socket programming involves building a client-server architecture where multiple clients can connect to a central server and communicate with each other in real-time. The chat room program is built in Python, leveraging the socket library to establish network communication between the server and clients.
The program begins with setting up a server that listens for incoming client connections. When a client connects, the server creates a new thread to handle the communication between the client and server. The server maintains a list of all connected clients and their respective threads.
Once clients are connected and identified, they can send messages to the server, which broadcasts them to all other connected clients. Additionally, the program handles disconnections, where clients can leave the chat room without causing any disruption to ongoing conversations.
The chat room program incorporates error handling mechanisms to handle various issues such as socket errors, connection errors, and disconnection errors. The program is scalable and can handle multiple conversations in real-time, providing a seamless chatting experience to users.
