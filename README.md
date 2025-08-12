# Network-traffic-analyzation-with-Wireshark


Capture Duration: 1 minute
Tool: Wireshark (Kali Linux)

Protocols Found:
1. ARP – Used to resolve IP addresses to MAC addresses within the LAN. Observed ARP requests and replies between local devices.
2. TCP – Reliable transport protocol used for most internet communication. Observed TCP three-way handshake packets (SYN, SYN-ACK, ACK).
3. DNS – Protocol for translating domain names into IP addresses. Observed DNS queries for domains visited during the capture.
4. ICMPv6 – IPv6 network diagnostic and neighbor discovery protocol. Observed Echo Requests/Replies and Neighbor Solicitation messages.

Observations:
- ARP traffic is local and not routed outside the LAN.
- TCP packets correspond to browsing activities and other app connections.
- DNS queries occur before TCP/HTTP connections to websites.
- ICMPv6 activity indicates the presence of IPv6 configuration and devices.

Conclusion:
The capture shows normal network activity including device discovery, domain resolution, and application traffic.
