# Week 3:  

## SSH (secure shell server) / Network Connection
- a program that allows connection to a remote system
- a program that is running on a computer all the time called a service or a Dameon
- stateful connection or network socket connection - connection stays open 
- a server listenening for an incoming connection from a client program (ex: SSH)
- A hacker would install a connection or a server so that it will accept client programs

SSH BY ENTERING: 'ssh username@ip address'

### NAT vs Bridged Connection
- NAT: Network Address Translation -routed connection with information packets 
- Bridge connection next to NAT inside, Bridge connection changes the IP Address
- NAT is a more secure connection 
- IP address is going to give the SSH connection 
- How to test SSH connection to localhost?

There would always be a pts on remote connection unless I was using an actual computer,
then it would be a TTY

The only way to get an actual ttu is if the console is plugged into the machine
   otherwise the connection is pts 
* ip a - show all ip addresses (ipconfig /all windows)
* clear - clears screen
* which - path to ssh
* type - "type of thing it is" displays more info than which 
* who - displays who is logged in and how 
* w - display logger version of who is logged in
* users - shortname of all logged in users 
* who I am - print effective username / ID
* last - summary of last logged in users 
* exit - exit the current program or log in or shell
* w - displays who is logged in and how 
* id - display user and group names and ids for self 
* | less | more - scrolling option 
* <ctrl> c - to interrupt
* <ctrl> d - semd end of data file
* Sudo apt install
* 
     
