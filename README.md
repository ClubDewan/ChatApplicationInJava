# ChatApplicationInJava
First, you will need to create the server-side of the application, which will listen for incoming connections from clients and handle messages received from them. You can use Java's ServerSocket class to create the server and wait for incoming connections.

Once a connection is established with a client, you can create a new thread to handle communication with that client. This will allow you to handle multiple clients concurrently and improve the performance of your application. You can use the Thread class in Java to create and manage threads.

On the client side, you will need to create a user interface for the chat application. This can be done using a library like Swing or JavaFX. The client will also need to connect to the server using a socket and send and receive messages through this connection.

To make the chat application work only on the local network, you can specify the IP address of the server in the client's code. This will ensure that the client can only connect to the server if both are on the same local network.
