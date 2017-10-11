# SI
## Laboratory works

**Send TCP messages**    
  Creating a TCP Server/Client first, (INET,STREAMing) socket type. Bind, listen,accept,recv and send functions here.

**Send UDP messages**  
  Creating a UDP Server/Client first, (INET,DGRAM) socket type. Here the server does not need to listen and accept connections, so we use only bind to associate the socket to a port and recvfrom to recieve the message. And in the client part I have the sendto, which send exactly to the indicated (IP,HOST).

**Send a file**  
  Tried to implement sending a txt file. Here also use the TCP socket.

**Port scanning**  
  Pogram asks for an address, then it turns it into an IPv4 address format using gethostbyname function. Create a socket and execute the connect function to get the connection results. Code is set to 0 when there's succesful result(open port??). Port scanning finds the open ports and prints them. This was a little bit more difficult for me to understand, but at least I tried.

More info in the pdf.
