# Chat-Messenger-with-Log-Facility

Project Type : Java Console Application
Modules      : ChatServerX.java, ChatClientX.java
Author       : Vaishnavi Shingare

## Project Overview

This project is a Java-based peer-to-peer chat application that enables real-time text-based communication
between users using Java Socket Programming.

Along with providing basic chat functionality, it also maintains a log file that records all conversation details in a
periodic fashion for future reference.

The application is platform and architecture independent, running on any system with a Java Runtime
Environment (JRE).

# Files Included:

| File Name         | 	Description                                |
|-------------------|----------------------------------------------|
| ChatServerX.java  | Java class for the chat server functionality |
| ChatClientX.java  | Java class for the chat client functionality |

## Key Features

• Peer-to-Peer Communication

◦ Uses Java sockets for direct communication between clients.

• Real-Time Chat

◦ Enables instant text-based messaging between connected peers.

• Chat Log Maintenance

◦ Logs all chat history with timestamps into a file.

◦ Provides periodic logging for organized record-keeping.

• Cross-Platform

◦ Runs seamlessly across different operating systems and architectures.

• Lightweight & Extensible

◦ Can be extended to support group chat, file sharing, or encryption.

# How to Compile and Run:

1. Compile the Java source files using terminal/command prompt:
   
   javac ChatServerX.java
   javac ChatClientX.java

2. Open two separate terminal windows:
   
   - In the first terminal, run the server:

```text
Chat Messenger with Log Facility is a Java-based application.
```   
  - In the second terminal, run the client:

       - java ChatClientX
   
3. Start chatting:

  - The client sends the first message.
  - The server responds to the message.
  - To end the conversation, type "end" in the client terminal.

# Sample Output:

# Server Terminal:

Marvellous Server is waiting at port number 5151

Marvellous Server successfully connected with the client

------ Marvellous Chat Messenger is Ready to Use ------

Client says: Hello
Enter the message for client: Hi, welcome!

# Client Terminal:

Client is ready to connect with server
Marvellous client is successfully connected with server
------ Marvellous Chat Messenger is Ready to Use ------
Hello
Server says: Hi, welcome!
Enter message for server:

# Protocol Used:

TCP/IP socket communication
Port: 5151
Communication: Synchronous (one message at a time)

# Termination:

To end the session, type "end" from the client side.
The server will stop interaction when client exits.

















