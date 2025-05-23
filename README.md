--- Simple TCP Client ---\n
A basic TCP client implementation in C that connects to a server and allows message exchange.\n
\n
> Features:\n
> Connects to a local TCP server on port 8080\n
> Allows sending messages to the server\n
> Receives responses from server\n
> Type "exit" to terminate the connection\n
\n
> Requirements\n
> Linux/Unix system\n
> GCC compiler\n
> Compile the program using gcc:\n
gcc tcp_client.c -o tcp_client\n
\n
> Usage:\n
> First, make sure the server is running on "127.0.0.1:8080"\n
> After compilation, make sure your client has execution permission
CHMOD +x tcp_client\n
> Run the client:\n
./tcp_client \n
> Type your message when prompted\n
> Type "exit" and press Enter to close the connection\n
\n
--- Important Notes ---\n
The server must be running before starting the client\n
This is a simple demonstration without robust error handling\n
Messages are limited to 1024 bytes\n
This code is provided as-is for educational purposes. Feel free to modify and use it as needed.
