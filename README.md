# task1_elevatelab

I performed a TCP SYN port scan on my local network to identify open services and captured the network traffic with Wireshark.

## Commands I ran
- Identify IP:
  - ip a
- Nmap SYN scan:
  - sudo nmap -sS -p 1-1000 192.168.xx.xxx/24 -oN scan_result.txt

## Findings (example)
- Host 192.168.xxx.xx — open ports: 53 (tcp)
- Several ports returned RST (closed). Some probes got no reply (filtered).

## Files included
- scan_results.txt — nmap text output
