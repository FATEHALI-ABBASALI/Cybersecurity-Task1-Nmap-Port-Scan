1. Quick Nmap Commands

I. Fast SYN scan
   • nmap -sS 192.168.1.0/24

II. Full TCP range
   • nmap -sS -p- 192.168.1.0/24

III. Service detection
   • nmap -sS -sV 192.168.1.0/24

IV. UDP scan (top 1000)
   • nmap -sU --top-ports 1000 192.168.1.0/24

V. Host discovery
   • nmap -sn 192.168.1.0/24
