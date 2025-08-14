# Module 2: Introduction to the Network Layer

---

## 🌐 The Network Layer Overview

The Network Layer is responsible for delivering packets between different networks. It ensures data can travel from a source device to a destination across routers and subnets.

---

## 📍 IPv4 Addresses

IPv4 addresses are 32-bit numerical labels assigned to devices. They're written in dotted decimal format (e.g., 192.168.1.1) and are essential for identifying devices on a network.

![IPv4 Address Format](images/IPv4_Address_Format.png)

---

## 📦 IPv4 Datagram and Encapsulation

Data is encapsulated in an IPv4 datagram, which includes headers (with fields like TTL, protocol, checksum) and a payload.

![IPv4 Datagram Structure](images/IPv4_Datagram_Structure.png)

---

## 🏷️ IPv4 Address Classes

IP addresses are categorized into classes (A, B, C, D, E) based on their leading bits. This helps segment large address spaces.

![IP Address Classes](images/IP_Address_Classes.png)

---

## 🔁 Address Resolution Protocol (ARP)

ARP maps IP addresses to MAC addresses, allowing devices to find one another on a local network.

![ARP Process Diagram](images/ARP_Process.png)

---

## 🔢 Subnetting and Subnet Masks

Subnetting divides large networks into smaller, manageable subnets using subnet masks.

![Subnetting Diagram](images/Subnetting_Example.png)

---

## 📐 CIDR Notation

CIDR (Classless Inter-Domain Routing) allows flexible allocation of IP addresses using notation like `/24` to define subnet masks.

---

## 🔣 Binary Math in Subnetting

Understanding binary is key for calculating subnets, determining ranges, and understanding IP classes.

![Binary Math Example](images/Binary_Subnetting.png)

---

## 🚦 Basic Routing Concepts

Routers determine how packets travel using routing tables that define the best next hop.

![Basic Routing Flow](images/Basic_Routing_Concepts.png)

---

## 🗺️ Routing Tables

Routing tables hold information like destination networks, subnet masks, next hops, and interfaces.

![Routing Table Example](images/Routing_Table_Example.png)

---

## 🔄 Interior vs Exterior Gateways

- **Interior Gateway Protocols (IGPs)**: Used within autonomous systems (e.g., OSPF, RIP).
- **Exterior Gateway Protocols (EGPs)**: Used between autonomous systems (e.g., BGP).

![IGP vs EGP](images/IGP_vs_EGP.png)

---

## 🛰️ Autonomous Systems and IANA

Autonomous systems (AS) are managed using unique ASN identifiers. The IANA oversees IP address distribution globally.

![ASN and IANA](images/ASN_IANA.png)

---

## 🔍 RFCs and Internet Standards

Protocols like RIP, OSPF, and BGP are defined in RFC documents maintained by the Internet Engineering Task Force (IETF).

![RFC Process](images/RFC_Process.png)

---

## 🚫 Non-Routable Address Space

Certain IP address ranges (e.g., 192.168.x.x) are reserved for internal use and are not routable on the internet.

![Private IP Ranges](images/Private_IP_Addresses.png)

---

## 📚 Glossary Highlights

- **IP Datagram**: A structured data unit in IPv4.
- **TTL (Time-To-Live)**: Limits the number of hops a packet can take.
- **Subnet Mask**: Defines the network portion of an IP.
- **Next Hop**: The next router to send the packet to.
- **NAT**: Allows private IPs to access the public internet.
- **CIDR**: Flexible IP allocation system (e.g., /22).

---

## 📘 Summary

In this module, you explored how data travels across networks using IP, routing protocols, and addressing systems. You learned about subnetting, ARP, CIDR, and the role of routers and protocols in forwarding data.

---

*Images used in this module:*

- IPv4_Address_Format.png  
- IPv4_Datagram_Structure.png  
- IP_Address_Classes.png  
- ARP_Process.png  
- Subnetting_Example.png  
- Binary_Subnetting.png  
- Basic_Routing_Concepts.png  
- Routing_Table_Example.png  
- IGP_vs_EGP.png  
- ASN_IANA.png  
- RFC_Process.png  
- Private_IP_Addresses.png

---
