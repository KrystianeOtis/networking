# Overview


To start this networking process both the server.py and client.py need to be downloaded an opened in an IDE. Start the server by running the server.py file first in the command prompt. Then open another command prompt and run client.py. The command prompt will then ask for a username. After inputing the username write a message and send it. Return back to the command prompt that was used to run the server. The message will be displayed there.

The purpose of this software is to show how a server and a client network works together.

This is a demonstration of how to use Python and the sockets library to network between server and a client.

[Software Demo Video](http://youtube.link.goes.here)

# Network Communication

I used a client server architecture and used TCP with my local IP address and an empty port.

I used Port 5054 (but I think you can use any port over 5,000 because those should be unoccupied)

The program will prompt for the username and after a message is sent the username will display with the message back at the server.

# Development Environment

* Python 3.100
* Socket library
* Visual Studio Code

# Useful Websites

* [Tutorialspoint](https://www.tutorialspoint.com/python/python_networking.htm)
* [Python Docs](https://docs.python.org/3/library/socket.html)

# Future Work

* Chat between multiple clients
* Make an appealing interface
* send files or images between clients
