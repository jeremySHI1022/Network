# Network
##TCP
###Compilation-
Server side:
gcc server.c -o server
./server

Client side:
gcc client.c -o client
./client

###Output-
Server side:
'Socket successfully created..
Socket successfully binded..
Server listening..
server acccept the client...
From client: hi
     To client : hello
From client: exit
     To client : exit
Server Exit... '
Client side:
'Socket successfully created..
connected to the server..
Enter the string : hi
From Server : hello
Enter the string : exit
From Server : exit
Client Exit... '


##UDP
###Output-
'$ ./server
Client : Hello from client
Hello message sent.
$ ./client
Hello message sent.
Server : Hello from server'
