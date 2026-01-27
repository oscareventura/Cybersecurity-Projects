# Network Scanning with Nmap

## Overview
This project demonstrates network reconnaissance using Nmap and Zenmap
to identify live hosts, open ports, and exposed services in a controlled
lab environment.

## Tools Used
- Nmap / Zenmap
- Windows 10 virtual machine
- Isolated lab network

## Techniques Demonstrated
- Host discovery
- Port scanning
- Service enumeration
- OS fingerprinting
- Firewall behavior analysis

## Example Commands
nmap -sn 192.168.1.0/24  
nmap -T4 -A -v 192.168.1.102  
nmap -T4 -A -v -Pn 192.168.1.102  

## Key Takeaways
- Open ports expand the system attack surface
- Reconnaissance is the first stage of most cyber attacks
- Firewalls can block host discovery without -Pn
- Defensive configuration directly affects scan results

## Disclaimer
All testing was performed in a controlled lab environment on systems I owned
or had explicit permission to test.
