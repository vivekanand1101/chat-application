# chat-application
Multi client chat application done as assignment for networking course

1. For communication between clients, the server must be started first.

## Running the chat application on localhost
### HOW TO START THE SERVER:
1. Run the server_frame.java file
2. Press the start button in the server

### HOW TO CONNECT THE CLIENT:
(Assumes you have started the server)
1. Existing User:
	1. Run the Home.java file
	2. Click on login
	3. Give the user, handle and password
	4. Click on connect. By default, it assumes the server to be on localhost
	5. If server is not on localhost, specify the server location and port
2. New User:
	1. Run the Home.java file
	2. Click on register
	3. Give the name, handle and password
	4. Click on connect. By default, it assumes the server to be on localhost
	5. If server is not on localhost, specify the server location and port

###Running the chat application on different machines

1. In the client project, each of the login, register and client_frame files (classes) have
   a class variable "address" which is initialized to "localhost", change it to the ip address
   of the server. Also, you can specify the port there, if the server port has changed.
2. There is no change in server code.
3. Everything rest is same as running on localhost

