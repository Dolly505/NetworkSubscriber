
Client using customized protocol on top of UDP protocol for requesting identification from server for access permission to the network.

Pre-requisite:
Install gcc on Linux for C program compiler

How to compile and run in Linux:

1.move within code folder. Open terminal at that folder.
2. Run the below commands to compile the C programs:
	gcc server2.c -o server2
	gcc client2.c -o client2
3. First the server should be started. To start the server, run:
	./server2
4. In a new terminal window, run below for running the client program:
	./client2
5. Packets would start transmitting and output would be visible
