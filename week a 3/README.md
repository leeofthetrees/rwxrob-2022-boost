# Week 3:  

## SSH (secure shell server) / Network Connection
- a program that allows connection to a remote system
- a program that is running on a computer all the time called a service or a Dameon
- stateful connection or network socket connection - connection stays open 
- a server listenening for an incoming connection from a client program (ex: SSH)
- A hacker would install a connection or a server so that it will accept client programs

### NAT vs Bridged Connection
- NAT: Network Address Translation -routed connection with information packets 
- Bridge connection next to NAT inside, Bridge connection changes the IP Address
- NAT is a more secure connection 
- IP address is going to give the SSH connection 
- How to test SSH connection to localhost?

The only way to get an actual ttu is if the console is plugged into the machine
   otherwise the connection is pts 
ip a - show all ip addresses (ipconfig /all windows)
clear - clears screen
which - path to ssh
type - "type of thing it is" displays more info than which 
who - displays who is logged in and how 
users - shortname of all logged in users 
