# Packet Analysis and Network Traffic Investigation Using Wireshark

## Overview

This project demonstrates the practical application of **network packet analysis** using **Wireshark**, one of the world's leading network protocol analyzers. Live network traffic was captured, filtered, and analyzed to examine how devices communicate across a network using common protocols such as **ARP, DNS, ICMP, TCP, and HTTPS/TLS**.

The project focuses on understanding packet structures, client-server communication, protocol behavior, and network conversation patterns while identifying potential anomalies that may indicate security threats or network performance issues.

---

## Objectives

- Capture live network traffic using Wireshark.
- Analyze common network protocols.
- Understand packet structures and communication flows.
- Examine the TCP three-way handshake.
- Monitor client-server communications.
- Identify network anomalies and Indicators of Compromise (IOCs).
- Develop practical skills in network monitoring and cybersecurity investigations.

---

## Scope of Analysis

The investigation covered the following areas:

- Packet Capture
- Protocol Identification
- Packet Filtering
- Client-Server Communication
- TCP Session Analysis
- DNS Resolution
- ARP Communication
- ICMP Traffic
- HTTPS/TLS Communication
- Network Conversation Statistics

---

## Protocols Analyzed

The following protocols were captured and analyzed during the investigation:

### Address Resolution Protocol (ARP)

- MAC address resolution
- Device discovery
- Broadcast requests
- ARP replies

### Domain Name System (DNS)

- DNS Queries
- DNS Responses
- Name Resolution
- Domain Lookups

### Internet Control Message Protocol (ICMP)

- Echo Requests (Ping)
- Echo Replies
- Network Reachability
- Latency Analysis

### Transmission Control Protocol (TCP)

- Three-Way Handshake
- Connection Establishment
- Sequence Numbers
- Acknowledgements
- Connection Termination

### HTTPS/TLS

- Secure Web Communication
- TLS Handshake
- Encrypted Application Traffic
- Certificate Exchange

---

## Tools Used

- Wireshark
- Windows Command Prompt
- Web Browser
- Ping Utility
- DNS Lookup Tools
- Network Interface Card (NIC)

---

## Investigation Methodology

The project followed these steps:

1. Configure Wireshark for packet capture.
2. Generate network traffic through browsing and network utilities.
3. Capture live packets.
4. Apply protocol-specific display filters.
5. Analyze packet headers and payload information.
6. Examine communication flows.
7. Review conversation statistics.
8. Document observations and findings.

---

## Wireshark Filters Used

Examples of display filters applied during the investigation:

```text
arp
dns
icmp
tcp
http
tls
ip.addr == <IP_Address>
tcp.port == 443
```

---

## Key Findings

The packet analysis successfully demonstrated:

- Successful packet capture from live network traffic.
- Proper ARP address resolution between hosts.
- DNS queries and responses for domain name resolution.
- ICMP Echo Request and Reply messages used for connectivity testing.
- TCP three-way handshake during client-server communication.
- Secure HTTPS/TLS sessions for encrypted web traffic.
- Network conversation statistics showing communication patterns between devices.

No evidence of malicious traffic was identified during the controlled laboratory exercise.

---

## Skills Demonstrated

This project demonstrates practical experience in:

- Network Traffic Analysis
- Packet Capture
- Protocol Analysis
- Wireshark Usage
- Network Troubleshooting
- Cybersecurity Monitoring
- Client-Server Communication Analysis
- TCP/IP Networking
- Incident Investigation
- Digital Forensics Fundamentals

---

## Learning Outcomes

Through this project, the following concepts were reinforced:

- TCP/IP Communication
- OSI Model
- Packet Structure
- Network Protocol Behavior
- Secure Communications
- Network Monitoring
- Traffic Filtering
- Communication Flow Analysis
- Cybersecurity Investigation Techniques

---

## Repository Structure

```text
Packet-Analysis-and-Network-Traffic/
│
├── README.md
├── Packet_Analysis_Report.pdf
├── packet-captures/
│   └── network_capture.pcapng
├── screenshots/
│   ├── arp-analysis.png
│   ├── dns-analysis.png
│   ├── tcp-handshake.png
│   ├── icmp-analysis.png
│   ├── tls-analysis.png
│   └── conversation-statistics.png
├── filters/
│   └── wireshark-filters.md
└── assets/
```

---

## Recommendations

To strengthen network visibility and security, organizations should:

- Implement continuous network monitoring.
- Regularly review network traffic for anomalies.
- Deploy Intrusion Detection/Prevention Systems (IDS/IPS).
- Use encrypted communication protocols.
- Maintain updated network documentation.
- Conduct routine packet analysis during incident investigations.
- Apply network segmentation to limit lateral movement.

---

## References

- Wireshark Documentation
- RFC 791 – Internet Protocol (IP)
- RFC 792 – Internet Control Message Protocol (ICMP)
- RFC 793 – Transmission Control Protocol (TCP)
- RFC 1035 – Domain Name System (DNS)
- NIST Cybersecurity Framework
- OWASP Security Guidelines

---

## Author

**Samuel Ochoche Peter**

**Data Analyst | Cybersecurity Enthusiast | IT Associate**

Passionate about network security, packet analysis, digital forensics, and cybersecurity monitoring through practical, hands-on investigations.

---

## License

This project is published for **educational, research, and portfolio purposes only**. All packet captures and analyses were conducted in an authorized laboratory environment.
