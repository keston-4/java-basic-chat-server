# ChatServer
This project is a simple chat client. There are three implementations.

Server - This starts up a server that can handle one client, when a client connected, the client and server can communicate.
AdvancedServer - This is similar to server, with the addition of multiple clients. This means multiple clients can talk to the server, however, they cannot talk to each other.
ChatServer - This is a simple chat server, clients connected and are given an ID, each client is able to send a message to each other.


To run:

Server must be started first:
javac <Server>.java - to compile
java <Server> <port>

Then the client can connect to the server:
javac Client.java - to compile
java Client <port> <address>
  The port and address are for the machine hosting the server. If it is local, then the address can be substituted for 'localhost'.
  Otherwise, enter the IP address or domain name.
 
