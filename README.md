# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
### client:
![alt text](2CCLIENT-IN.png)
### server:
![alt text](2CSERVER-IN.png)
## OUPUT - ARP
### client output:
![alt text](2CCLIENT-OUT.png)
### server output:
![alt text](2CSERVER-OUT.png)
## PROGRAM - RARP
### client:
![alt text](2C2CLIENT.png)
### server:
![alt text](2C2SERVER.png)

## OUPUT -RARP
### client output:
![alt text](2C2CLIENT-OUT.png)
### server output:
![alt text](2C2SERVER-OUT.png)
## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
