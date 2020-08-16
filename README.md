# LiveCode-HTTP-Server
Example LiveCode Stack that HTTP Server services in native LiveCode.  It uses the "contents/Tools/Extensions/com.livecode.library.httpd/httpd.livecodescript" library found in LiveCode desktop application.

LiveCode is a compile free language so you can run and edit your application live, allowing you to add code gradually, and develop iteratively, testing as you go, with no compile time or delay. ... That means you can build any application you create to run on Windows, Mac OS, Linux, iOS, Android or a server.
https://livecode.com or http://livecode.org/ for open source version

This stack adds the function to determine the content type of a file before the server responses to a browser client request.  This allow you to use this server as a localhost server so you can host your html website on your local machine.

The sample web site is a free product of https://amp.dev.
AMP is a web component framework to easily create user-first websites.
https://github.com/ampproject/ampstart/blob/master/LICENSE

This sample is only for illustration purposes to demonstrate a typical webpage root directory structure and would be replaced by your own webpage directory.

The default server port is set to http://localhost:8080/ but you can change this is by editing the Server port field.

The "Activate Server Log" checkbox turns on logging function that is displayed in the "Server Log" field. This function needs to be selected before "Starting" the server.  It will be cleared if you deselect it while the server running.

The "Root Directory" field displays the full directory path to the "index.html" file.  The server uses this to find the "index.html" file and all other resource files. By default it will be set to the html server stack path where it will expect to find the "index.html" file.

The Server Name field can be empty since code will use a default value of "LiveCode Server" but you can name it anything you wish aand it will be passed into the webpage header.

This stack and a sample web site can be downloaded from https://github.com/merill00/LiveCode-HTTP-Server
