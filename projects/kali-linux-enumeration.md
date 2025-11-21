# Kali Linux Network Recon & Enumeration

## Goal
Gain familiarity with host discovery and service enumeration to better understand how attackers map environments and how defenders interpret scan data.

## Lab Setup
- Kali Linux VM
- One or more target VMs on an isolated network
- Tools: nmap, ping, basic shell utilities

## What I Did
1. Verified connectivity to target systems using ping.
2. Used `nmap -sn` to identify active hosts on the subnet.
3. Used `nmap -sV` to enumerate services and versions on a selected host.

## Key Findings
- Identified common ports and services exposed in the lab environment.
- Observed how scan intensity and flags change visibility.
- Learned to read nmap results from a defender’s point of view.

## Relevance to a Security Role
Improves understanding of reconnaissance techniques, supports better interpretation of IDS/IPS alerts, and informs hardening and exposure-reduction decisions.

## Tools Used
Kali Linux, nmap
