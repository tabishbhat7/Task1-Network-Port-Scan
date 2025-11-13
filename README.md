# Task 1 – Scan Your Local Network for Open Ports

**Date:** Thu Nov 13
## Tools
- Nmap (Windows)
- Npcap (installed via Nmap installer)

## Commands used
- Find IP: `ipconfig`
- Network scan: `nmap -sS 192.168.x.0/24 -oN my_scan.txt`
- Service/version check: `nmap -sV 192.168.x.y -oN host_192.168.x.y.txt`

## Files included
- `my_scan.txt` — full network scan output
- `README.md` — this file

## Summary of findings
- PORT      STATE  SERVICE  
22/tcp    open   ssh  
80/tcp    open   http  
139/tcp   open   netbios-ssn  
445/tcp   open   microsoft-ds  
3389/tcp  open   ms-wbt-server 

## Notes / Recommendations
- Close or secure unnecessary services.
- Change default credentials on devices.
- Keep firmware and OS updated.
