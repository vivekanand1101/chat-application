# chat-application
Multi client chat application done as assignment for networking course

* For communication between clients, the server must be started first.

## Running the chat application on localhost
### HOW TO START THE SERVER:
* Run the server_frame.java file
* Press the start button in the server

### HOW TO CONNECT THE CLIENT:
(Assumes you have started the server)
#### Existing User:
* Run the Home.java file
* Click on login
* Give the user, handle and password
* Click on connect. By default, it assumes the server to be on localhost
* If server is not on localhost, specify the server location and port
#### New User:
* Run the Home.java file
* Click on register
* Give the name, handle and password
* Click on connect. By default, it assumes the server to be on localhost
* If server is not on localhost, specify the server location and port

###Running the chat application on different machines

* In the client project, each of the login, register and client_frame files (classes) have
   a class variable "address" which is initialized to "localhost", change it to the ip address
   of the server. Also, you can specify the port there, if the server port has changed.
* There is no change in server code.
* Everything rest is same as running on localhost

