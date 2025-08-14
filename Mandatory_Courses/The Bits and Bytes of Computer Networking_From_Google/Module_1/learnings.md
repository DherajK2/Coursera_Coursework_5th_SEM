# Module 1 Learnings

---

## Topics Covered
- TCP/IP Five-Layer Network Model  
- OSI Networking Model (Supplementary)  
- Importance of Networking  
- Cables, Hubs, Switches, Routers, Servers & Clients  
- Moving Bits Across the Wire  
- Twisted Pair Cabling & Duplexing  
- Ethernet Over Twisted Pair Technologies  
- Network Ports, Patch Panels & Cabling Tools  
- Ethernet & MAC Addresses  
- Unicast, Multicast, Broadcast  
- Ethernet Frame Structure  
- Glossary of Key Terms  

---

## TCP/IP Five-Layer Network Model  
The TCP/IP model consists of five layers: Physical, Data Link, Network, Transport, and Application. This layered architecture enables communication between devices by defining how data is packaged, addressed, transmitted, routed, and received.

![TCP/IP Model](tcp_ip_model.png)

---

## OSI Networking Model (Supplementary)  
The OSI model has seven layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application. It provides a detailed framework for network communication and protocol development.

![OSI Model](osi_model.png)

---

## Why Networking is Important  
Networking connects devices to share data, resources, and access the internet. It supports communication in homes, businesses, and across the globe, enabling services like email, video calls, and cloud computing.

![Networking Importance](networking_importance.png)

---

## Cables, Hubs, Switches, Routers, Servers & Clients  

- **Cables** physically connect devices allowing data transmission.  
- **Hubs** broadcast data to all connected devices, operating at the physical layer.  
- **Switches** intelligently forward data only to the destination device using MAC addresses, working at the data link layer.  
- **Routers** connect different networks, directing data based on IP addresses.  
- **Servers** provide resources and services to clients, which request and use those services.

![Network Devices](network_devices.png)

---

## Moving Bits Across the Wire  
Data is transmitted as electrical signals (copper cables), light pulses (fiber optics), or radio waves (wireless). The physical medium affects speed, distance, and quality of communication.

![Data Transmission](data_transmission.png)

---

## Twisted Pair Cabling & Duplexing  
Twisted pair cables reduce electromagnetic interference by twisting wire pairs. Duplex communication can be:  
- **Full Duplex:** simultaneous two-way data flow.  
- **Half Duplex:** communication in one direction at a time.

![Twisted Pair Cabling](twisted_pair_cable.png)

---

## Ethernet Over Twisted Pair Technologies  
Ethernet cables (CAT5, CAT6) use twisted pairs for reliable, low-cost networking in homes and businesses. They transmit both data and voice signals.

![Ethernet Twisted Pair](ethernet_twisted_pair.png)

---

## Cable Types  
- **Unshielded Twisted Pair (UTP):** Most common, affordable, basic interference protection.  
- **Shielded Twisted Pair (STP):** Includes shielding to protect against EMI and RFI.  
- **Foiled Twisted Pair (FTP):** Uses foil shielding for added interference protection.

![Cable Types](cable_types.png)

---

## Cable Uses: Straight-Through vs. Crossover  
- **Straight-through cables:** Connect different device types (e.g., PC to switch). Both ends have identical wiring.  
- **Crossover cables:** Connect similar devices (e.g., PC to PC). Wiring on each end is crossed to align transmit and receive pairs. Mostly replaced by Auto-MDI/MDIX technology.

![Straight-Through vs Crossover](straight_crossover_cables.png)

---

## Network Ports & Patch Panels  
Physical ports and patch panels organize cable connections in structured cabling systems, providing easy management and scalability.

![Patch Panel](patch_panel.png)

---

## Cabling Tools  

- **Crimper:** Attaches connectors to cables by squeezing them in place.  
- **Cable Stripper:** Removes the outer cable jacket.  
- **Wi-Fi Analyzer:** Measures signal strength and quality.  
- **Toner Probe:** Locates cables by producing audible tones.  
- **Punch Down Tool:** Inserts wires into patch panels or keystone jacks.  
- **Cable Tester:** Checks cable integrity and wiring.  
- **Loopback Plug:** Tests network ports by looping signals back.  
- **Network Tap:** Copies network traffic for monitoring without interrupting flow.

![Cabling Tools](cabling_tools.png)

---

## Ethernet & MAC Addresses  
Every network device has a unique MAC address (48-bit), used to identify hardware in local networks and manage data transmission at the data link layer.

---

## Unicast, Multicast & Broadcast  
- **Unicast:** One sender to one receiver.  
- **Multicast:** One sender to multiple specific receivers.  
- **Broadcast:** One sender to all devices on the LAN.

---

## Ethernet Frame Structure  
An Ethernet frame contains:  
- **Preamble:** Synchronizes communication.  
- **Start Frame Delimiter (SFD):** Marks the start of the frame.  
- **Destination & Source MAC:** Identifies sender and receiver.  
- **EtherType:** Indicates the protocol.  
- **Payload:** The actual data.  
- **Frame Check Sequence (FCS):** Error checking.

---

## Glossary (Selected Terms)  
- **Bit:** Smallest unit of data.  
- **Broadcast:** Transmission to all devices.  
- **Collision Domain:** Network segment where collisions occur if multiple devices transmit simultaneously.  
- **Duplex:** Two-way communication capability.  
- **Hub:** Device broadcasting data to all ports.  
- **Router:** Connects different networks.  
- **Switch:** Forwards data intelligently based on MAC addresses.

---

*End of Module 1 Learnings*
