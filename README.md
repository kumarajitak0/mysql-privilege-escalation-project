#  MySQL Database Exploitation & Privilege Escalation (with Defensive Remediation)

## Project Overview

This project demonstrates a full security lifecycle from a red-team perspective (attacker) and a blue-team (defender) response:

- Simulating an attack on a misconfigured MySQL database from Kali Linux.
- Gaining access via brute-force attack.
- Privilege escalation by creating a new admin user.
- Capturing and analyzing database traffic using Wireshark.
- Applying hardening and monitoring defenses to secure the system.

This project was executed entirely on virtual machines using Oracle VirtualBox:  
- Kali Linux (Attacker)  
- Ubuntu Server 20.04 (Target)

---

# Tools Used

| Purpose             | Tool/Software          
|---------------------|------------------------
| Attacker VM         | Kali Linux             
| Target VM           | Ubuntu Server 20.04    
| Database            | MySQL 5.7              
| Port Scanner        | Nmap                   
| Brute-force Tool    | Hydra                  
| Packet Sniffer      | Wireshark              
         |
