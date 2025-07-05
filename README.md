# Multithread-Chat-Application

Company:CODTECH IT SOLUTIONS

Name: Padmasri V.G

Intern ID:CT04DH1472

Domain:Java Development

Duration:4 weeks

Mentor:Neela Santosh

Description:

This project is a multithreaded client-server chat application developed using Java sockets, enabling real-time communication between multiple users over a local network. It showcases the principles of network programming, multithreading, and client-server architecture in Java. The system allows users to join a chat session, exchange messages, and see others' messages in real time — making it a basic yet powerful foundation for building messaging systems.

Tools & Technologies Used:

Programming Language: Java

Networking API: java.net.Socket, java.net.ServerSocket

Multithreading: Thread, Runnable interface

Input/Output Streams: BufferedReader, PrintWriter for stream-based communication

Development Environment: IntelliJ IDEA (can also be compiled and run using Command Prompt or VS Code)

Java Version: Java 17

 Key Features:

Supports multiple client connections simultaneously using multithreading.

Each client runs on a separate thread, ensuring smooth concurrent communication.

Messages sent by one client are broadcast to all other connected clients.

Simple text-based interface for input/output (can be extended to GUI).

Includes username identification, allowing users to tag their messages with names.

 How it Works:

Server Side:

A single server socket listens on a specific port (e.g., 1234).

Each time a client connects, the server spawns a new thread for that client.

Messages received from a client are relayed to all others via broadcasting.

Client Side:

Each client connects to the server via a socket.

Users input messages through the console.

Messages are tagged with the username and sent to the server.

The client also listens for incoming messages and displays them in real-time.

 Real-World Applications:

This project provides a foundation for building:

Instant messaging systems (e.g., WhatsApp backend basics)

Customer support live chats

Real-time collaborative tools

Gaming lobby chats

Group discussion tools for classrooms and organizations

While simple, the same logic is used in scaled-up versions of real-time systems and chat servers (like those powered by WebSocket in production apps).

 Educational Value:

This project is ideal for students or beginners who want to:

Understand TCP socket programming

Learn how to handle multiple clients simultaneously

Practice object-oriented programming and thread safety

Grasp how servers can manage concurrent connections

Conclusion: 

This multithreaded chat application serves as a practical demonstration of Java’s networking and concurrency features. It is a strong foundational project that can be expanded further — by adding GUI support using Swing/JavaFX, encryption for security, file transfers, or even database integration for chat history. Overall, it’s a great hands-on learning tool for anyone entering the field of network and systems programming.

Output:

<img width="1919" height="1010" alt="Image" src="https://github.com/user-attachments/assets/e37c47b7-586c-442c-8877-e13720d2bc81" />

<img width="1919" height="1007" alt="Image" src="https://github.com/user-attachments/assets/8590087e-0a69-409b-bddd-47fbe5a9ade5" />

<img width="1915" height="1004" alt="Image" src="https://github.com/user-attachments/assets/1f3aed75-dbf4-4481-b0ac-3c0709df73f5" />
