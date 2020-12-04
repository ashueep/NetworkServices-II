# Network Services

## SMB

  1. Server Message Block Protocol - is a client-server communication protocol used for sharing access to files, printers, serial ports and other resources on a network. 
  2. The SMB protocol is known as a response-request protocol, meaning that it transmits multiple messages between the client and server to establish a connection. Clients connect to servers using TCP/IP

## Enumerating SMB

  Typically, there are SMB share drives on a server that can be connected to and used to view or transfer files.

## Enum4linux

  Enum4linux is a tool used to enumerate SMB shares on both Windows and Linux systems.

|TAG      |     FUNCTION|
|---------|-------------|
|-U       |      get userlist|
|-M        |     get machine list|
|-N      |       get namelist dump (different from -U and-M)|
|-S      |       get sharelist|
|-P       |      get password policy information|
|-G      |       get group and member list|
|-A      |       all of the above (full basic enumeration)| 
