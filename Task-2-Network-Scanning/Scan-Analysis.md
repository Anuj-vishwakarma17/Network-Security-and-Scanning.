# Detailed Scan Analysis Report

## Target Information

Target IP: 192.168.244.4
Scanner: Kali Linux

Tools Used:

- Nmap
- Nessus Essentials
- Wireshark

---

## Reconnaissance Analysis

Tool Used:
netdiscover

Analysis:
The target system was successfully discovered in the network. This confirms the system is active and reachable.

Security Impact:
Active systems can be scanned and potentially exploited.

---

## Nmap Scan Analysis

Command Used:
nmap -sS -sV -O 192.168.244.4

Findings:

Open Ports:

- Port 21 – FTP
- Port 22 – SSH
- Port 23 – Telnet
- Port 80 – HTTP
- Port 3306 – MySQL

Analysis:

These open ports indicate exposed services running on the system.

Security Risk:

- FTP may contain backdoor vulnerability
- Telnet is insecure protocol
- Outdated services may be exploitable

Attackers can use these services as entry points.

---

## Nessus Vulnerability Analysis

Tool Used:
Nessus Essentials

Findings:

- Critical vulnerability detected
- Backdoor service identified
- Outdated services detected

Analysis:

The backdoor vulnerability allows unauthorized access.

Security Risk:

Attackers can exploit this vulnerability to gain system access.

---

## Wireshark Traffic Analysis

Tool Used:
Wireshark

Filter Used:
http

Findings:

HTTP login request captured.

login.php request observed.

Analysis:

Credentials and login traffic were visible in plain text.

Security Risk:

Unencrypted HTTP traffic can be intercepted.

HTTPS should be used.

---

## Final Conclusion

The assessment successfully identified open ports, vulnerabilities, and network traffic.

This demonstrates real-world vulnerability assessment workflow using professional tools.
