# Task 1: Local Network Port Scan using Nmap

## Objective
Discover open ports on devices in the local network to understand network exposure.

## Tools Used
- OS: Kali Linux
- Tool: Nmap

## Steps Performed
1. Identified local IP and subnet using `ip a`
2. Scanned the network for live hosts using `nmap -sn`
3. Scanned specific hosts for open ports using `nmap -sS`
4. Detected services and OS with `nmap -sV -O`

## Files
- `output.txt`: Contains full scan logs and results

## Notes
This scan was conducted in a controlled environment (my own network) for educational purposes.
