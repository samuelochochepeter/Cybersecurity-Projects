# Design and Implementation of a Secure Enterprise Network Using VLANs and Inter-VLAN Routing

## Overview

This project presents the design and implementation of a **secure enterprise banking network** using **Virtual Local Area Networks (VLANs)** and **Inter-VLAN Routing** in **Cisco Packet Tracer**. The network was designed to simulate a real-world enterprise environment where multiple departments require logical network segmentation, secure communication, and centralized network management.

The implementation demonstrates how VLANs improve network security, performance, scalability, and manageability by separating departments into different broadcast domains while allowing controlled communication through **Router-on-a-Stick (Inter-VLAN Routing)**. To further enhance security, **Access Control Lists (ACLs)** were configured to enforce communication policies between departments.

---

## Project Objectives

The objectives of this project were to:

- Design a secure enterprise network topology using Cisco Packet Tracer.
- Implement VLANs for logical network segmentation.
- Configure VLAN names and assign switch ports.
- Implement IP addressing for all network devices.
- Configure trunk links between switches and routers.
- Implement Inter-VLAN Routing using the Router-on-a-Stick technique.
- Configure Access Control Lists (ACLs) to enforce security policies.
- Verify connectivity using network testing tools.
- Demonstrate secure communication between departments.
- Gain practical experience in enterprise networking and cybersecurity.

---

## Enterprise Network Scenario

The simulated organization consists of four departments:

- Customer Service
- Accounts Department
- Information Technology (IT)
- ATM / Server Infrastructure

Each department operates within its own VLAN and IP subnet to ensure secure communication and network isolation.

---

## Network Topology

The enterprise network consists of:

- Cisco Router
- Cisco Layer 2 Switch
- Multiple PCs
- ATM Server
- Dedicated VLANs
- Trunk Links
- Router-on-a-Stick Configuration

---

## VLAN Configuration

| VLAN ID | Department | Network |
|---------:|------------|----------------|
| 10 | Customer Service | 192.168.10.0/24 |
| 20 | Accounts | 192.168.20.0/24 |
| 30 | Information Technology | 192.168.30.0/24 |
| 40 | ATM / Server | 192.168.40.0/24 |

---

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- VLAN Configuration
- Inter-VLAN Routing
- Router-on-a-Stick
- Access Control Lists (ACLs)
- IPv4 Addressing
- Switch Port Configuration
- Trunk Configuration
- Network Troubleshooting

---

## Key Networking Concepts

This project demonstrates the practical implementation of:

- VLAN Segmentation
- Inter-VLAN Routing
- Router-on-a-Stick
- Static IP Addressing
- Switch Port Assignment
- Trunk Links (802.1Q)
- ACL-Based Security
- Enterprise Network Design
- Secure Network Communication
- Network Troubleshooting

---

## Security Controls Implemented

The following security measures were implemented:

- Departmental Network Segmentation
- VLAN Isolation
- Access Control Lists (ACLs)
- Controlled Inter-VLAN Communication
- Restricted Access to IT Resources
- Protected ATM/Server Network
- Router-Based Security Policies

---

## Network Testing and Verification

The following tests were successfully performed:

- VLAN Verification
- Interface Status Verification
- IP Address Verification
- Trunk Link Verification
- Inter-VLAN Connectivity Tests
- ACL Enforcement Tests
- Ping Connectivity Tests
- Network Troubleshooting

All verification tests confirmed that the enterprise network operated as expected and that security policies were successfully enforced.

---

## Skills Demonstrated

This project demonstrates practical experience in:

- Enterprise Network Design
- Cisco Packet Tracer
- VLAN Configuration
- Inter-VLAN Routing
- Router Configuration
- Switch Configuration
- Network Security
- Access Control Lists (ACLs)
- IP Addressing
- Network Troubleshooting
- Enterprise Infrastructure Design

---

## Learning Outcomes

This project strengthened practical knowledge in:

- Enterprise Network Architecture
- VLAN Deployment
- Network Segmentation
- Secure Routing
- Cisco IOS Configuration
- Enterprise Security Controls
- Communication Flow Management
- Cybersecurity Best Practices

---

---

## Recommendations

To further improve enterprise network security:

- Deploy Layer 3 switches for larger environments.
- Implement Dynamic Routing Protocols (OSPF or EIGRP).
- Configure Port Security on access ports.
- Enable DHCP Snooping and Dynamic ARP Inspection.
- Deploy Intrusion Detection/Prevention Systems (IDS/IPS).
- Implement Network Access Control (NAC).
- Monitor traffic using SIEM solutions.
- Regularly review ACLs and network configurations.

---

## References

- Cisco Networking Academy
- Cisco IOS Documentation
- RFC 791 – Internet Protocol
- RFC 826 – Address Resolution Protocol
- IEEE 802.1Q VLAN Standard
- NIST Cybersecurity Framework
- CISA Network Security Best Practices

---

## Skills and Technologies

- Cisco Packet Tracer
- VLANs
- Inter-VLAN Routing
- Router-on-a-Stick
- Access Control Lists (ACLs)
- IPv4 Networking
- Cisco IOS
- Enterprise Network Security
- Network Segmentation
- Network Administration

---

## Author

**Samuel Ochoche Peter**

**Data Analyst | Cybersecurity Enthusiast | IT Associate**

Passionate about enterprise networking, cybersecurity, secure infrastructure design, and implementing practical networking solutions using industry-standard technologies.

---

## License

This project is published for **educational, research, and portfolio purposes only**. All network configurations and security implementations were performed within an authorized laboratory environment.
