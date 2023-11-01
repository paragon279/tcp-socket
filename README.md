# Simple TCP Server-Client C++ Example

This C++ example demonstrates a basic TCP server-client interaction using sockets.

## Usage (Linux)

### Server

1. Open a terminal and navigate to the directory where your C++ source code is located (referred to as `INTO_CPP_FOLDER`).

2. Compile the server code with the following command:
   ```
   cd INTO_CPP_FOLDER
   g++ tcp-Server.cpp -o server
   ```
Run the server, specifying the port number to listen on (e.g., 8080):

```
./server 8080
```
### Client
Open another terminal and navigate to the directory where your C++ source code is located (INTO_CPP_FOLDER).

Compile the client code with the following command:

```
cd INTO_CPP_FOLDER
g++ tcp-Client.cpp -o client
```

Run the client, specifying the server's IP address (e.g., 127.0.0.1) and the same port number used by the server (e.g., 8080):

```
./client 127.0.0.1 8080
```

Note: This example is intended for local usage only. Adjust the server IP address and port as needed for your specific setup.
