# HTTP-2_server
User Documentation for HTTP/2 Server

Introduction
This document provides detailed instructions for installing, configuring, and using the HTTP/2 server. The server supports both HTTP/1.1 and HTTP/2 protocols, serving static files, handling GET and POST requests, and supporting most HTTP/2 RFC features.

Prerequisites
1.	Python 3.8 or higher installed on your system.
2.	Basic knowledge of command-line usage.
3.	Required Python libraries:
o	socket
o	threading
o	os
o	keyboard
o	h2 (for HTTP/2 support)
o	hashlib
o	time

To install h2 library, run this command in your favorable command-line: 
> pip install h2


Usage
Starting the Server
1.	Open a terminal or command prompt.
2.	Navigate to the directory containing the server.py script.
3.	Run the server using:   
>  python server.py

4.	The server will start and display the following message:
==================================================
         [INFO] HTTP Server running on <your-ip>:<port>
==================================================

Accessing the Server
1.	Open a web browser (which doesn’t usually support HTTP2) or an HTTP client.
2.	Use the server's host and port in the URL:
o	http://<your-ip>:<port>/
3.	If HTTP/2 is enabled, the server will automatically detect and handle HTTP/2 requests.

!!! That’s it, the server should be working !!!




