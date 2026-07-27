# Network Traffic Analysis

## Overview

This project demonstrates the use of Wireshark to capture and analyze network traffic generated during normal network activity. The purpose of this project was to gain hands-on experience identifying common network protocols, understanding packet structure, and learning how network communication occurs between devices.

Throughout this project, packet captures were analyzed to identify ICMP, DNS, TCP, and TLS traffic while documenting the role each protocol plays in modern computer networks.

---

## Objectives

- Capture live network traffic using Wireshark
- Identify common network protocols
- Analyze ICMP traffic
- Analyze DNS traffic
- Analyze TCP connections
- Observe encrypted TLS traffic
- Practice basic packet analysis

---

## Lab Environment

| Component | Details |
|-----------|----------|
| Operating System | macOS |
| Packet Analyzer | Wireshark |
| Network Interface | Wi-Fi (en0) |
| Traffic Generated | Web browsing and ICMP Ping |

---

## Skills Demonstrated

- Packet Capture
- Network Traffic Analysis
- Protocol Identification
- Basic Network Troubleshooting
- Wireshark Filtering
- Cybersecurity Fundamentals

---

## Investigations

- Live Packet Capture
- ICMP Packet Analysis
- DNS Packet Analysis
- TCP Packet Analysis
- TLS Packet Analysis
- Protocol Hierarchy Statistics

---

## Lessons Learned

This section will summarize the knowledge and experience gained after completing the project.

---

# Investigation 1. Live Packet Capture

## Objective

Capture live network traffic using Wireshark to observe real time network communications.

## Procedure

The active Wi-Fi interface (en0) was selected in Wireshark and a live packet capture was started. While the capture was running, normal web browsing activity was performed to generate common network traffic for analysis.

## Screenshot

![Live Packet Capture](Screenshots/01-live-packet-capture.png)

## Findings

The packet capture immediately displayed multiple network protocols communicating across the local network. Wireshark identified the source address, destination address, protocol type, packet length, and additional details for each packet.

This demonstrated how Wireshark provides real time visibility into network communications and serves as an essential tool for network troubleshooting and cybersecurity investigations.

