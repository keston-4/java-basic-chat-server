# Basic Chat Server (Java)
This project is a simple chat client. There are three implementations.

**Server**<br />
This starts up a server that can handle one client, when a client connected, the client and server can communicate.

**MultiServer**<br />
This is similar to server, with the addition of multiple clients. This means multiple clients can talk to the server, however, they cannot talk to each other.

**ChatServer**<br />
This is a simple chat server, clients connected and are given an ID, each client is able to send a message to each other.


**To run:**<br />
_Server must be started first:_<br />
`javac [ServerType].java` - to compile<br />
`java [ServerType] [port]`<br />
<br />
_Then the client can connect to the server:_<br />
`javac Client.java` - to compile<br />
`java Client [port] [address]`<br />
  The port and address are for the machine hosting the server. If it is local, then the address can be substituted for 'localhost'.
  Otherwise, enter the IP address or domain name.
 
