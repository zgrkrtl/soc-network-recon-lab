┌──(root㉿kali)-[/home/kali]
└─# nmap -sS -T4 10.0.2.5    
Starting Nmap 7.95 ( https://nmap.org ) at 2026-03-13 15:50 EDT
Nmap scan report for 10.0.2.5
Host is up (0.0011s latency).
All 1000 scanned ports on 10.0.2.5 are in ignored states.
Not shown: 1000 filtered tcp ports (no-response)
MAC Address: 08:00:27:EC:FC:3B (PCS Systemtechnik/Oracle VirtualBox virtual NIC)

Nmap done: 1 IP address (1 host up) scanned in 25.09 seconds
                                                                                        
┌──(root㉿kali)-[/home/kali]
└─# nmap -sV 10.0.2.5    
Starting Nmap 7.95 ( https://nmap.org ) at 2026-03-13 15:54 EDT
Nmap scan report for 10.0.2.5
Host is up (0.0010s latency).
All 1000 scanned ports on 10.0.2.5 are in ignored states.
Not shown: 1000 filtered tcp ports (no-response)
MAC Address: 08:00:27:EC:FC:3B (PCS Systemtechnik/Oracle VirtualBox virtual NIC)

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 27.16 seconds
                                                                                        
┌──(root㉿kali)-[/home/kali]
└─# nmap -A 10.0.2.5
Starting Nmap 7.95 ( https://nmap.org ) at 2026-03-13 15:56 EDT
Nmap scan report for 10.0.2.5
Host is up (0.0011s latency).
All 1000 scanned ports on 10.0.2.5 are in ignored states.
Not shown: 1000 filtered tcp ports (no-response)
MAC Address: 08:00:27:EC:FC:3B (PCS Systemtechnik/Oracle VirtualBox virtual NIC)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   1.11 ms 10.0.2.5

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 34.55 seconds
                                                                
