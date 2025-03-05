# TryHackMe Walkthrough
### Room: Easy Peasy

I choose this room because the description said it focused on enumeration using Nmap and Gobuster. I thought it would be a good review for me so I got started in it.
After connecting my Kali VM to the target machine in this room, I started off with scanning for the open ports and services.

```sudo nmap -sS -sV -p- <target_IP> -oA result```

The flags `-p-` tells nmap to scan all ports, `-sS` tells nmap to do SYN scan, `-sV` tells nmap to check the version of the services it finds, the `-oA` tells nmap to write the scan result into files in all format with "result" as its based-name.
Nmap can scan multiple targets IP at once, but since we have only 1 target in this room, I did not put it in a separated file called "targetsList.txt".

Here is the screenshot of it.
<insert screenshot>

To be continue