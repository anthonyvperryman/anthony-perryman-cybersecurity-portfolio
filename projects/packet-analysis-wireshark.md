# Packet Capture & Analysis – Wireshark

## Goal
Build confidence reading packet flows, spotting anomalies, and troubleshooting network issues using Wireshark in a controlled home lab.

## Lab Setup
- Windows 10 VM and a Linux VM
- Tools: Wireshark, browser, ping, nslookup
- Traffic: web browsing, DNS lookups, and simulated connectivity issues

## What I Did
1. Captured traffic on the primary network interface while browsing, performing DNS lookups, and running ping tests.
2. Applied filters for DNS, HTTP/HTTPS, ICMP, and SYN packets.
3. Compared normal browsing patterns to failed DNS lookups and connection timeouts.

## Key Findings
- Observed complete DNS query/response cycles.
- Identified failed DNS queries and linked them to connectivity issues.
- Practiced recognizing incomplete TCP handshakes and unusual spikes in traffic.

## Relevance to a Security Role
These skills support PCAP review, incident investigation, and differentiating between misconfigurations and potentially malicious activity.

## Tools Used
Wireshark, Windows 10, Linux
