#The original code belongs to Copyright (C) 2001,2005 by Jarno Elonen <elonen@iki.fi>

#This modification adds support to specify custom directory and file to run the server

How to use:

NanoHTTPD nanoServer = new NanoHTTPD(8567);

//params for server
String[] arg = {"90", "C:\Users\naverse\github\nanoweb\"}

//to start server
nanoServer.startServer(arg);

//to stop server
nanoServer.stopServer();