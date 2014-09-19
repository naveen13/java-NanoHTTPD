How to use:

NanoHTTPD nanoServer = new NanoHTTPD(8567);

//params for server
String[] arg = {"90", "C:\Users\naverse\github\nanoweb\"}

//to start server
nanoServer.startServer(arg);

//to stop server
nanoServer.stopServer();