WinMessage v0. Based off of the Bitmessage protocol.

TODO:

- Connections
 
	-	Create timer to maintain the network health.(attempt a connection to each node on the list every 20 mins?).
	-	if a connection drops, remove it from the connection list.(the list is for active connections only).
	-	create counters to keep track of lists
	-	stop deleting nodes if the list goes under 1000
	-	max nodes == 20 000
	-	create Ping and Pong functions	
	-	start connecting to network?


- Messaging
	-	make sure all objects are stored as vectors when we receive them or create them.
	-	create a list for Address's that is seperate from the Vectors list
	-	modify appropriate functions to reflect the above change.
	-	create the function to handle pubkey incoming objects
	-	finish the handling of public keys (sending & receiving)



Thanks To:

- Thanks to @c_07 from CodeProject.com
	-	"The source code is NOT copyrighted and you may use it, modify it, and mess around with it to your heart's content, because it's too simple to copyright. HOWEVER, this does not apply to the tutorial..."(Taken from the readme)
	-	http://www.codeproject.com/Articles/13071/Programming-Windows-TCP-Sockets-in-C-for-the-Begin

- Copyright
	-	Go ham. Encryption for all.