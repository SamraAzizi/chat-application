# 1. Instant Messaging App

This is a simple instant messaging application implemented in Java, consisting of a server (server.java) and a client (client.java). The server and client communicate over sockets to enable real-time messaging between multiple clients.

## Features
Server-Client Communication: The server and client communicate over sockets, allowing messages to be sent and received in real-time.
Simple User Interface: Although not included in the code provided, the application can be extended with a graphical or command-line user interface (UI) for a more user-friendly experience.


## Usage<br>
## Server (server.java)
1. Compile the server.java file.<br>
&nbsp;&nbsp;&nbsp;&nbsp;javac server.java

2. Run the server.<br>
&nbsp;&nbsp;&nbsp;&nbsp;java server<br>
&nbsp;&nbsp;&nbsp;&nbsp;The server will start and wait for clients to connect.

## Client (client.java)<br>
1. Compile the client.java file.

&nbsp;&nbsp;&nbsp;&nbsp;javac client.java<br>
2. Run the client.<br>
&nbsp;&nbsp;&nbsp;&nbsp;java client<br>
Enter messages in the client's console and press Enter to send them to the server. The client will receive responses from the server and display them in the console.
