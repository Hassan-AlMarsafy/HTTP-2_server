# HTTP-2_server<br/>
User Documentation for HTTP/2 Server<br/>

Introduction<br/>
This document provides detailed instructions for installing, configuring, and using the HTTP/2 server. The server supports both HTTP/1.1 and HTTP/2 protocols, serving static files, handling GET and POST requests, and supporting most HTTP/2 RFC features.<br/>

Prerequisites<br/>
1.	Python 3.8 or higher installed on your system.<br/>
2.	Basic knowledge of command-line usage.<br/>
3.	Required Python libraries:<br/>
o	socket<br/>
o	threading<br/>
o	os<br/>
o	keyboard<br/>
o	h2 (for HTTP/2 support)<br/>
o	hashlib<br/>
o	time<br/>

To install h2 library, run this command in your favorable command-line: <br/>
> pip install h2<br/>


Usage<br/>
Starting the Server<br/>
1.	Open a terminal or command prompt.<br/>
2.	Navigate to the directory containing the server.py script.<br/>
3.	Run the server using:   <br/>
>  python server.py<br/>

4.	The server will start and display the following message:<br/>
==================================================<br/>
         [INFO] HTTP Server running on <your-ip>:<port><br/>
==================================================<br/>

Accessing the Server<br/>
1.	Open a web browser (which doesn’t usually support HTTP2) or an HTTP client.<br/>
2.	Use the server's host and port in the URL:<br/>
o	http://<your-ip>:<port>/<br/>
3.	If HTTP/2 is enabled, the server will automatically detect and handle HTTP/2 requests.<br/>

!!! That’s it, the server should be working !!!<br/>




