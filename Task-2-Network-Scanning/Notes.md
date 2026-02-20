# Task-2 Notes: Network Scanning & Vulnerability Assessment

## Host Discovery

Tool Used:
netdiscover

Purpose:
Identify active hosts in the local network.

Command:
netdiscover

Result:
Target IP successfully identified.

---

## Connectivity Verification

Tool Used:
ping

Command:
ping 192.168.xx.xx

Purpose:
Verify communication between attacker and target.

---

## Information Gathering

Tool Used:
whois

Command:
whois 192.168.xx.xx

Purpose:
Gather target system information.

---

## Nmap Scanning

Tool Used:
Nmap

Command:
nmap -sS -sV -O 192.168.xx.xx

Purpose:
- Identify open ports
- Detect running services
- Detect operating system

Result:
Multiple open ports detected including FTP, SSH, HTTP, MySQL.

---

## Nessus Vulnerability Scan

Tool Used:
Nessus Essentials

Purpose:
Detect vulnerabilities in target system.

Result:
- Critical vulnerability detected
- Backdoor service identified
- Multiple security weaknesses found

---

## Wireshark Analysis

Tool Used:
Wireshark

Filter Used:
http

Purpose:
Capture and analyze HTTP traffic.

Result:
DVWA login request captured and analyzed.

---

## Summary

The tools successfully identified:

- Active hosts
- Open ports
- Running services
- Vulnerabilities
- Network traffic
