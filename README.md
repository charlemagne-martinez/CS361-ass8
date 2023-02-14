# CS361-ass8
Assignment 8 for CS361. 

Communication Contract for microservice (currently). 

Currently, this microservice uses sockets in python to showcase its functionality. 
There is a server python file as well as a client python file. The client python 
file is requested to enter either '1' to request to the server to randomly generate
a number and send that back to the client, or to enter 'quit' to quit both the 
server and the client. 

To start up, this microservice, you would have two terminal windows open, one for the
server and one for the client. First, you would enter 'python3 server.py' to start
up the server in one terminal window followed by 'python3 main.py' to start up the 
client in the other terminal window. Afterwards, in the terminal for the client, you 
will be prompted to either enter '1' or 'quit'. To request for data (randomly generated 
number), in the terminal for the client, you would enter '1'. Once you enter '1', this will
be sent to the server, and on the terminal for the server, you would see that it received 
that '1' that the client entered. Following this, the server will randomly generate a number.
To receive this randomly generated number on the client side, the server will send that number
via sockets. Finally, on the client side terminal window, you would see which random special
item would be added to one's shopping list, based on the randomly generated number that the
server generated and sent back to the client. 
