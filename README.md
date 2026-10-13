# Wireshark Network Traffic Analysis

## Project Overview
This project demonstrates basic network traffic analysis using Wireshark. It focuses on DNS traffic inspection and TCP three-way handshake verification.

## Objectives
- Analyze DNS packets.
- Identify source and destination IP addresses.
- Understand TCP SYN, SYN-ACK, and ACK flags.
- Practice Wireshark display filters.
- Develop basic SOC Analyst Level 1 investigation skills.

## Tools Used
- Wireshark
- Web browser
- Windows

## Practical Tasks

### 1. DNS Traffic Analysis
Display filter:
`dns`

Used to inspect DNS queries and identify requested domain names.

### 2. TCP Traffic Analysis
Display filter:
`tcp`

Used to view TCP packets.

### 3. Initial SYN Packets
Display filter:
`tcp.flags.syn == 1 && tcp.flags.ack == 0`

Used to identify initial TCP connection requests.

### 4. SYN-ACK Packets
Display filter:
`tcp.flags.syn == 1 && tcp.flags.ack == 1`

Used to identify server responses during TCP connection establishment.

### 5. TCP Stream Verification
Display filter:
`tcp.stream eq N`

Replace `N` with the actual TCP stream index observed in Wireshark. This helps inspect packets belonging to one connection.

## TCP Three-Way Handshake
1. SYN — Client requests a connection.
2. SYN-ACK — Server responds.
3. ACK — Client acknowledges the response.
## Wireshark Screenshots

### 1. DNS Traffic Analysis
![DNS Analysis](screenshots/dns-analysis.png)

### 2. TCP SYN Analysis
![TCP SYN Analysis](screenshots/tcp-syn-analysis.png)

### 3. TCP Three-Way Handshake
![TCP Handshake](screenshots/tcp-handshake.png)
## Learning Outcomes
- Learned basic DNS packet inspection.
- Practiced TCP display filters.
- Learned the TCP three-way handshake.
- Practiced examining packets in a TCP stream.

## Evidence
Screenshots and a practical analysis report will be added after documenting the actual capture results.

## Conclusion
This beginner project builds foundational skills in network traffic analysis relevant to SOC Analyst Level 1.

**Note:** Findings and screenshots should reflect my own authorized Wireshark practice.
