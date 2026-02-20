# Network Scanning & Vulnerability Assessment Cheat Sheet

## Host Discovery

netdiscover

arp-scan --localnet

---

## Connectivity Test

ping <target-ip>

---

## Information Gathering

whois <target-ip>

nslookup <target-ip>

---

## Nmap Commands

Basic Scan:
nmap <target-ip>

Service Detection:
nmap -sV <target-ip>

OS Detection:
nmap -O <target-ip>

Advanced Scan:
nmap -sS -sV -O <target-ip>

Aggressive Scan:
nmap -A <target-ip>

---

## Nessus

Start Nessus:
sudo systemctl start nessusd

Open in browser:
https://127.0.0.1:8834

---

## Wireshark Filters

HTTP filter:
http

ICMP filter:
icmp

DNS filter:
dns

TCP filter:
tcp

---

## Useful Linux Commands

Check IP:
ip a

Check network:
ifconfig

Check connectivity:
ping <target-ip>

Clear terminal:
clear
