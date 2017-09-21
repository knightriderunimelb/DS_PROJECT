Shared whiteboards allow multiple users to draw simultaneously on a canvas. There are multiple examples found on the Internet that support a range of features such as freehand drawing with the mouse, drawing lines and shapes such as circles and squares that can be moved and resized, and inserting text. In addition to these features, your implementation should include a simple chat window, that allows all the current users of the system to broadcast messages to each other. 
Develop a white board that can be shared between multiple users over the network.
The system must be implemented in Java but you can choose the technology (e.g., it can be even Sockets) you want to use to build your distributed application: 
Sockets 
TCP or UDP?
Message format? (JSON suggested)
Exchange protocol?
E.g., client broadcasts a message with updates to all other clients, other clients reply acknowledging the message.
Java RMI 
Remote Objects? 
Remote Interface?
 Databases for Storage

 Dealing with concurrency 
Regardless of the technology you use, you will have to ensure that access to shared resources is properly handled and that simultaneous actions lead to a reasonable state.
Structuring your application and handling the system state 
For example you can have multiple servers that communicate with each other or a single central one that manages all the system state.
Dealing with networked communication 
You have to decide when/what messages are sent across the network. 
You may have to design an exchange protocol that establishes which messages are sent in which situation and the replies that they should generate. 
If you use RMI, then you have to design your remote interface(s) and servants
Implementing the GUI. 
The functionality can resemble tools like MS Paint.
You can use any tool/API/library you want.
e.g.: Java2D drawing package (http://docs.oracle.com/javase/tutorial/2d/index.html) 


