# NetworkingSamples
Provides sample code for TCP socket programming. The samples are provided to demonstrate specific concepts and are not scalable solutions. The programs can connect remotely much like they can locally. Simple change the target IP address in the client (be it in a textbox or particular line of code), then open the appropriate port for the server. And do not ask me how to connect them remotely. If you cannot connect them remotely, it is not a problem with the programs.


## BasicAsyncClient
A WinForms application that demonstrates asynchronous connect and send using the “Begin” and “End” methods. Uses custom/manual serialization.
## BasicAsyncServer
A WinForms application that demonstrates asynchronous connect and send using the “Begin” and “End” methods. Uses custom/manual serialization.
## MultiClient
A console application demonstrating a client that is used to connect to a server that accepts multiple clients. Sends and receives simple strings.
## MultiServer
A console application demonstrating multiple client connections. It uses asynchronous accept and receive, and synchronous send. Sends and receives simple strings.
## SyncSocketsConsole
Demonstrates synchronous sockets in a very simple solution. Both the client and server are part of the same console application. The console application starts in client-mode when the “/c” command-line switch is provided to it. It starts in server-mode when the “/s” command-line switch is provided to it.
