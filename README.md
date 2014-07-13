cs454-ta-simple-tcp-exG
======================

a simple example demonstrating tcp based on beej client server example

Based on http://beej.us/guide/bgnet/output/html/multipage/clientserver.html

Server std out:

		server: waiting for connections...
		server: got connection from 127.0.0.1

Client std out:

		client: connecting to 127.0.0.1
		read 4 bytes
		read a: 4
		read 4 bytes
		read b: 5

Tried to reporudce a students problem but was unable to:

		I am doing two sends (lets say the numbers  4 and 9). If on the server side if I
		attempt to continuously receive, I am getting 4, 32569 (dont know what this is)
		and then 9. 
