## ChatApplication with 4 bots.

A typical multi-threaded Chat Client/Server Java application

## Features
. Simple authentication with server. Users' info is stored as text file on the server side.



## How To Run
The server and client are initially configured to run locally. To run it on a different network, port forwarding is advised. We also need to change the hostName variable in SignInView.java. The client needs to know the server's WAN address.

First run the server, and then run the client.

## Bots
You can add more bots to the server as long as the bot implements the Bot.java interface. The new bot should also be instantiated in ChatServer.java file and assigned to a command character.
