# SNS Assignment2 - Implementation of Error Detection used in Computer Communications for Data Link Layer Security using Python
- **Dipankar Saha - 2020201084**

# Connection 

- **SERVER**: python3 server.py 127.0.0.1 <ANY_FREE_PORT>
- **CLIENT**: python3 client.py <SAME_IP_AS_ABOVE> <SAME_PORT_AS_ABOVE> (multiple clients can be connected to server at the same time)
  
# Functionality :
- User can type any message and press enter to send 
- Message will be encrypted using cipher matrix 
- The encrypted message along with the calculated CRC on original message will be send to server 
- Server will decrypt the messaage and calculate CRC of the decrypted message 
- If received CRC and calculated CRC matches then server will display the received message along with the sender details.
- If not server will display received data is corrupt along with the sender details
- Client with show error message and stops the sending process if it typed other than A-Z and space.
- Client can type exit or exit() to stop. Server will show the client's status.

## NOTE: 
Cipher matrix and inverse of cipher matrix is declared manually in client and server respectively.
