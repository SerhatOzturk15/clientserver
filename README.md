# clientserver
client-server c project

In this project clients send information about files, and provide a keyword. The server gets the request and it computes number of occurences of that keyword and in which lines that keyword appears. In this project, all the operations are thread-safe, it does not matter how many clients ask for information from the server. Process and thread logics are used in the project as well as POSIX library for messaging between client and server.
