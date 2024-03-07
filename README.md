# 1. Instant Messaging App

This is a simple instant messaging application implemented in Java, consisting of a server (server.java) and a client (client.java). The server and client communicate over sockets to enable real-time messaging between multiple clients.

## Features
Server-Client Communication: The server and client communicate over sockets, allowing messages to be sent and received in real-time.
Simple User Interface: Although not included in the code provided, the application can be extended with a graphical or command-line user interface (UI) for a more user-friendly experience.


## Usage<br>
## Server (server.java)
1. Compile the server.java file.<br>
&nbsp;&nbsp;&nbsp;&nbsp;javac server.java

2. Run the server.
java server<br>
&nbsp;&nbsp;&nbsp;&nbsp;The server will start and wait for clients to connect.

## Client (client.java)<br>
1. Compile the client.java file.<br>

&nbsp;&nbsp;&nbsp;&nbsp;javac client.java
2. Run the client.<br>
&nbsp;&nbsp;&nbsp;&nbsp;java client<br>
Enter messages in the client's console and press Enter to send them to the server. The client will receive responses from the server and display them in the console.


# 2. Voice Chat Application
This is a simple voice chat application implemented in Java, consisting of a client (VoiceChatClient.java) and a server (VoiceChatServer.java). The application allows users to establish a voice chat connection over a network, enabling real-time communication.

## Features
Real-time Voice Chat: Users can establish a voice chat connection with each other and communicate in real-time.
Graphical User Interface (GUI): The application includes a graphical user interface (GUI) for user interaction, making it easier to initiate and manage voice chat sessions.

## Usage<br>
## Server (VoiceChatServer.java)*

1. Compile the VoiceChatServer.java file.<br>
&nbsp;&nbsp;&nbsp;&nbsp;javac VoiceChatServer.java

2. Run the server.<br>
&nbsp;&nbsp;&nbsp;&nbsp;java VoiceChatServer
The server will start and wait for clients to connect.

## Client (VoiceChatClient.java)
1. Compile the VoiceChatClient.java file.<br>

&nbsp;&nbsp;&nbsp;&nbsp;javac VoiceChatClient.java
2. Run the client.<br>
&nbsp;&nbsp;&nbsp;&nbsp;java VoiceChatClient

Enter the host name and port number of the server in the GUI.

Click the "Connect" button to establish a voice chat connection.

To hang up or quit the application, click the "Hang up/quit" button.


## Contact
For any questions or feedback, please feel free to contact the project maintainer at samarraazizi@gmail.com.