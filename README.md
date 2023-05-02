# tcp-server-client
# Title: Student Search Server

# Description:
This project implements a server that listens for incoming client connections, receives a search query from the client, and searches for the query in a data file containing student records. The server returns the result to the client if the search query is found, and sends a message indicating that the search query was not found if it is not present in the data file.

# Files:

server.cpp: C++ source code for the server application.
data.txt: A text file containing student records.
# Requirements:

Windows Operating System
C++ Compiler (Visual Studio recommended)
# Usage:

Compile the server.cpp source file using a C++ compiler.
Run the compiled server executable.
Connect to the server from a client program and send a search query.
# Limitations:

The server only supports searching for student records using exact matches. It does not support partial matches or fuzzy searches.
The data file must be in a specific format with each student record on a new line.
The server only supports a single client connection at a time.
The server does not support multithreading or asynchronous IO.
# Contributors:

Yahya Haj Ali
