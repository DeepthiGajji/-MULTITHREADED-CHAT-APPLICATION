# -MULTITHREADED-CHAT-APPLICATION

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:GAJJI DEEPTHI

*INTERN ID*:CT04DZ129

*DOMAIN*:JAVA PROGRAMMING

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

##DESCRIPTION

Multithreaded Chat Application 

This Java program demonstrates a real-time client-server chat application using Java Sockets and multithreading. The application allows multiple clients to connect to a central server and exchange messages simultaneously, simulating a simple chat room environment.

Key Features:

Server-Client Architecture

The server listens on a specific port and accepts incoming client connections.

Each client can connect to the server and send messages to other clients through the server.

The architecture ensures that the server manages multiple clients efficiently.

Multithreading for Concurrent Users

Each client connection is handled by a separate thread on the server.

This allows multiple clients to communicate simultaneously without blocking each other.

Threads are responsible for reading messages from clients and broadcasting them to all connected users.

Real-Time Messaging

Messages sent by one client are instantly delivered to all other clients connected to the server.

The chat interface displays messages with the sender’s information, maintaining clarity in conversations.

Error Handling and Robustness

The program handles common network errors, such as disconnections or invalid inputs.

It ensures that the server remains operational even if one client disconnects unexpectedly.

Technologies and Classes Used

java.net.ServerSocket and java.net.Socket – For establishing server and client connections.

java.io.BufferedReader and java.io.PrintWriter – For sending and receiving messages.

java.lang.Thread – To create separate threads for handling multiple clients concurrently.

java.util.List or java.util.concurrent.CopyOnWriteArrayList – To maintain a thread-safe list of connected clients.

Use Cases:

Real-time chat applications for learning and experimentation.

Multiplayer games or collaborative applications requiring real-time communication.

Understanding Java networking and multithreading concepts in practice.

Conclusion:
This program provides a hands-on example of building networked applications in Java. It demonstrates the integration of sockets, multithreading, and I/O streams to create a functional chat system that supports multiple users communicating in real time. The project highlights key concepts in concurrency, networking, and client-server programming.
