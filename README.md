
1. Objective
Analyze DNS traffic using Wireshark and understand DNS record types and security risks.

2. Tools Used
- Wireshark
- nslookup
- Web browser

3. Procedure
- Captured DNS traffic while visiting websites.
- Filtered packets using "dns" filter.
- Identified DNS record types (A, AAAA, CNAME).
- Observed query names and response IPs.

4. My findings :
- A records links domain names to IPv4 addresses which uses 32-bit (192.168.1.1).
- AAAA records links domain names to IPv6 addresses which uses 128-bit (2001:0db8:85a3::8a2e:0370:7334).
- CNAME records show domain aliases.
- No suspicious DNS traffic detected.

5. Research to find more way a system could be attacked:
- DNS Spoofing redirects users to fake sites.
- DNS Tunneling hides data inside DNS traffic.
- Cache Poisoning corrupts DNS records.

6. Screenshots

<img width="1470" height="956" alt="dnspackets" src="https://github.com/user-attachments/assets/eb92fd06-1ace-45bb-a197-9b415fbae523" />

<img width="1470" height="956" alt="recordtypeA" src="https://github.com/user-attachments/assets/b8007438-7093-4e33-aecd-4032dd84edfb" />

<img width="1470" height="956" alt="recordtypeAAAA" src="https://github.com/user-attachments/assets/f2ff4cd1-0049-4cea-bff6-845a2f445544" />

<img width="1470" height="956" alt="recordtypeHTTPS" src="https://github.com/user-attachments/assets/5ba17f8d-fadb-4da0-ae84-443106b52878" />

<img width="1470" height="956" alt="Query:ResponseIP" src="https://github.com/user-attachments/assets/fc4def2a-ad92-468f-81fb-6fca4ce58936" />

<img width="562" height="370" alt="TerminalMX" src="https://github.com/user-attachments/assets/b5041495-273e-4db5-8cfb-906c0a84bbf4" />


7. What I Learned?
- Practicing this lab improved my understanding of DNS traffic concepts, analysis and basic cybersecurity monitoring. 
