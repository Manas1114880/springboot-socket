

to run the project:
# mvn clean install package spring-boot:run

To follow the guide:
https://spring.io/guides/gs/messaging-stomp-websocket/

This project is going to use STOMP with JQuery on the client side and Spring-boot on the server.

To make the magic work, we are going to "model" the type of information our app is going to need to run, set up end-points to initiate actions, and core logic to drive our app.


## Where's the code?
src/main/java/com/example/messagingstompwebsocket

The is where the server-side source code lives. You can tell this by looking at the POM file at lines 11 and 12 of POM.xml (it is at the very bottom of your files list in Replit)
<pre>
	<groupId>com.example</groupId>
	<artifactId>messaging-stomp-websocket</artifactId>
</pre>
...src/main/java is the default location of all java packages.

### Entry point:
MessagingStompWebsocketApplication.java


