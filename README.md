# Task 1 – Network Port Scanning

## Objective
The objective of this task was to scan my local system and find open ports using Nmap.

## Tool Used
- Nmap

## Command Used
nmap -T4 -A -v 192.168.0.115

## Results
I scanned the IP address 192.168.0.115 in my local network.

The scan detected:
- Operating System: Windows
- Open Ports:
  - 135/tcp (MSRPC)
  - 139/tcp (NetBIOS)
  - 445/tcp (SMB) -(windows file sharing)

## Security Observation
Port 445 is used for file sharing in Windows. If not secured properly, it can be a security risk. 

## Conclusion
This task helped me understand how to perform port scanning using Nmap and identify open services in a local network. I also  gained basic knowledge about network security basics and open ports etc.
