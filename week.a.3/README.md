# Week 3 / SSH & Networking Examples

What is the console?  'Either a phywical phyical console or a digital equivalent,' 
* the phywical thing in front of you
* Each one has a tty

addtl info unrelated: 
* any process running on a computer can be spied on with a peace pipe written in go.
* pty is a pseudo terminal 
* tty makes it easier to spot than an application (after breaking into a system)

####.....Goal is to connect to Windows Terminal using SSH....####
* i am assuming that we are connectiong Windows Terminal to a Virtual Machine

daemon- "serving me" program running on computer all the time
 * **listens all the time for incoming connections**

stateful connection-
* **the connection is kept open**
* a stateful network socket connection

client 
* wants to dial up and talk to a server
* is something that want to dial into a server and keep a connection
VS a browser connects to a website and then done. (It doesn't maintain the connection)

https://www.youtube.com/watch?v=Pfk-KxO3in8&t=15772s

  #console #connection #stateful #client #browser #server #daemon
