<img width="906" height="434" alt="image" src="https://github.com/user-attachments/assets/093c886f-3d06-4d9a-84f7-bb0019d409d8" />
# Week2-Project-
Week-2 Project - Network Reconnaissance &amp; DNS Analysis using theHarvester, Wireshark and Nmap. Includes DNS analysis, packet capture and vulnerability scanning.
# Week-2 Project - Network Recon & DNS Analysis

*Name:* Malavika K.
*Date:* 12-Nov-2026
*Tools:* theHarvester, Wireshark, Nmap, Ping

## PM1-PM5: Reconnaissance
Collected DNS records, subdomains using theHarvester.
File: theharvester-result.json

## PM6: Wireshark Packet Capture
- ICMP: 10.0.0.128 -> 8.8.8.8 Echo request / reply
- DNS: google.com A / AAAA query / response
File: Week2-PM6.pcapng

## PM7: Vulnerability Scan
- nmap --script vuln -p 53 10.0.0.1 -> 53/tcp filtered
- nmap --script vuln -p 53,80,443 10.0.0.128 -> all filtered
Result: No vulnerability found, system secure.

## Conclusion
DNS, packet capture and vulnerability scan completed successfully.
