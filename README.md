# nmap-open-ports-lab 
## Description:
Network reconnaissance of Metasploitable 2 using Kali Linux.
## Goal:
Discover open ports, identify services, and analyze the attack surface.
## Commands Used
ping -c 4 <Target-IP>: Verify connectivity.
nmap <Target-IP>: Basic scan for open TCP ports.
nmap -sV <Target-IP>: Service version detection.
nmap -O <Target-IP>: OS detection (type, family, device).
nmap -A <Target-IP>: Full aggressive scan (OS, versions, scripts, traceroute).
## Key Concepts
OS Fingerprinting: Identifying the target's operating system.
Attack Surface: The total sum of open ports and services reachable by an attacker.
## Analysis:
Results: Open ports and running services identified via -sV.
OS: Linux-based system detected via -O.
Risk: Open ports represent potential threat vectors.
Mitigation: Reduce attack surface by closing unused ports and hardening services.
