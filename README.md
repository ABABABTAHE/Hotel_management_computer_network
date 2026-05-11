# Hotel Management System Network Design

A complete Hotel Management System Network Design project implemented using Cisco Packet Tracer for the Computer Networks Lab course.

##  Project Overview

This project focuses on designing and implementing a scalable and secure hotel network infrastructure. The network is divided into multiple VLANs for different departments across three floors of the hotel.

The project demonstrates:
- VLAN configuration
- Inter-VLAN communication
- DHCP implementation
- OSPF routing
- Wireless networking
- Router and switch configuration


##  Network Structure

### 1st Floor
| Department | VLAN | Network |
|------------|------|----------|
| Reception | VLAN 80 | 192.168.8.0/24 |
| Store | VLAN 70 | 192.168.7.0/24 |
| Logistics | VLAN 60 | 192.168.6.0/24 |

### 2nd Floor
| Department | VLAN | Network |
|------------|------|----------|
| Finance | VLAN 50 | 192.168.5.0/24 |
| HR | VLAN 40 | 192.168.4.0/24 |
| Sales | VLAN 30 | 192.168.3.0/24 |

### 3rd Floor
| Department | VLAN | Network |
|------------|------|----------|
| Admin | VLAN 20 | 192.168.2.0/24 |
| IT | VLAN 10 | 192.168.1.0/24 |


##  Router Connections

| Connection | Network |
|------------|----------|
| Router 1 ↔ Router 2 | 10.10.10.0/30 |
| Router 2 ↔ Router 3 | 10.10.10.4/30 |
| Router 1 ↔ Router 3 | 10.10.10.8/30 |


## ⚙️ Technologies Used

- Cisco Packet Tracer
- VLAN
- DHCP
- OSPF Routing Protocol
- Wireless Networking
- Router-on-a-Stick Configuration


##  Features

- Dynamic IP allocation using DHCP
- Efficient routing using OSPF
- VLAN-based departmental segmentation
- Inter-floor communication
- Wireless connectivity for devices
- Secure and scalable network design



##  Verification Commands

```bash
ping
show vlan brief
show ip route
```


##  Results

- All VLANs configured successfully
- Devices receive IP addresses dynamically
- Departments communicate efficiently
- OSPF advertises routes correctly
- Network connectivity verified successfully

##  Course Information

**Course Title:** Computer Networks Lab  
**Course Code:** CSE 2106  

##  Conclusion

This project successfully implements a modern hotel network infrastructure with VLAN segmentation, DHCP configuration, and OSPF routing. The design ensures secure, organized, and efficient communication between all hotel departments.
