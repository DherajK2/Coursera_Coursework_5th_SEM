# Module 3 challenge: The Five-Layer Network Model

1. Computer 1 on network A, with IP address of 10.1.1.205, wants to send a packet to Computer 2, with IP address of 172.16.1.57. On which network is computer 2?  
**Answer:** Network C

2. Computer 1 wants to send a packet to Computer 2. Since computer 2 is not on the local network, Computer 1 checks the ARP table for the corresponding ______ that matches the gateway IP.  
**Answer:** MAC address

3. Which layer constructs the Ethernet frame?  
**Answer:** Data link layer

4. What information is in the data payload of the Ethernet frame?  
**Answer:** IP datagram

5. When constructing the Ethernet datagram to send the packet from Router Z to Computer 2 which is on Network C, what information needs to be in the destination MAC address?  
**Answer:** Computer 2’s MAC address

6. Computer 1 on Network A sends a packet to Computer 2 on Network C. What's the last step that Router Z does after receiving the Ethernet frame?  
**Answer:** Decrements the TTL by 1, calculates a new checksum, and makes a new IP datagram. This new IP datagram is again encapsulated on a new Ethernet frame.

7. Computer 1 on network A, with IP address of 10.1.1.8, wants to send a packet to Computer 2, with IP address of 172.16.1.64. If the TTL value was set to 64 at the beginning, what is the value of the TTL once it reaches its destination?  
**Answer:** 62

8. Computer 1 on network C, with IP address of 172.16.1.57, wants to send a packet to Computer 2, with IP address of 192.168.1.14. Taking into consideration that computer 1 is sending a request to a web server on computer 2, listening on port 80, and the source port on computer 1 is 5000, which of the following contains the correct information for the fourth TCP segment of data?  
**Answer:**  
Source Port: 5000  
Destination Port: 80  
Sequence Number: 4  
Acknowledgment Number: 5

9. Computer 1 on network B, with IP address of 192.168.1.233, wants to send a packet to Computer 2, with IP address of 172.16.1.133. Which of the following has the correct IP datagram information for the fields: Version, minimum Header Length, Source IP, and Destination IP?  
**Answer:**  
Version: 4  
Header Length: 20  
Source IP Address: 192.168.1.233  
Destination IP address: 172.16.1.133

10. The ________ layer is responsible for sending ones and zeros through a process called modulation from Computer 1 to Computer 2.  
**Answer:** Physical
