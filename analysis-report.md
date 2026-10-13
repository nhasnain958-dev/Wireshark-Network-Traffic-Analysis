# Wireshark Network Traffic Analysis Report

## 1. Objective
To practice basic network traffic analysis using Wireshark and understand DNS queries, TCP flags, and TCP connections.

## 2. DNS Traffic Analysis
**Filter used:** `dns`

- Observed DNS packets in Wireshark.
- Examined source IP and destination IP.
- Inspected DNS query names.

## 3. TCP Flags Analysis
**Filter used:** `tcp.flags.syn == 1`

- Identified TCP packets with the SYN flag set.
- Practiced distinguishing initial SYN and SYN-ACK packets.

## 4. TCP Stream Analysis
**Filter used:** `tcp.stream eq N`

- Inspected packets belonging to one TCP stream.
- Practiced identifying SYN, SYN-ACK, and ACK in the expected order.

*Note: Replace N with the actual stream number from your capture.*

## 5. Conclusion
This project provided hands-on practice with Wireshark display filters, DNS traffic inspection, TCP flags, and TCP stream analysis. These are foundational skills for investigating network activity as a SOC Analyst Level 1.

## 6. Evidence
Screenshots of DNS analysis, TCP flags, and TCP stream analysis are included in the repository README.
