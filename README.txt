******* Instructions to Execute File System Project ***********
******* Course [CSE5306] ********* Project 01 ***************

Note: These instructions are for a Windows based machine

1. Open command prompt. Type CD [space] [path to the Server folder]
2. Type java -jar FileSystemServer.jar and press enter
3. The server would ask you if you want a single-threaded environment or multi-threaded. Enter 1 for single-threaded server and 2 for multi-threaded server.
4. Now, open another command prompt. Type CD [space] [path to the Client folder]
5. Type java -jar FileSystemClient.jar and press enter
6. The client would ask if you want the Dropbox synchronization on or off. Type "on" or "off".
7. The client would then give you a list of commands to execute. Enter the appropriate command to execute it. Following are the list of commands:
	a. Upload
	b. Download
	c. Delete
	d. Rename
	e. Exit
8. If the Dropbox synchronization is on, the client will synchronize with the server every 15 seconds
9. Synchronization is done for the following:
	a. File created
	b. File deleted
	c. File altered

NOTE: The client folder contains test.txt which is used as a base file for all operations

NOTE: When a file is renamed, all future operations will be performed on the renamed file on server-side


*******************************************************************************************************************************************************************
					END			END			END			END
