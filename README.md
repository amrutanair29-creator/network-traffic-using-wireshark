When analyzing captured traffic in Wireshark, the findings typically include:
1. Network Protocols Observed:
You can identify which protocols are active in the capture, such as TCP, UDP, HTTP, DNS, ARP, HTTPS, etc. This helps you understand the type of communication occurring on the network.
2. Source and Destination Details:
Wireshark displays the source and destination IP addresses and MAC addresses, helping you track communication between devices.
3. Packet Flow and Sequence:
You can observe how packets flow between clients and servers, including handshakes (like TCP 3-way handshake), retransmissions, acknowledgments, and data transfer patterns.
4. Packet Length and Timing:
Each packet shows its size, timestamp, and time delta from previous packets, useful for detecting delays, performance issues, or congestion.
5. Info Field Insights:
The “Info” column provides summary details like:
HTTP GET/POST requests
DNS queries and responses
TCP SYN, ACK, FIN flags
Errors such as “TCP Retransmission” or “Malformed Packet”
6. Filtering and Analysis:
Using display filters (e.g., ip, tcp, http, dns), you can isolate specific traffic types to focus on suspicious or important packets.
7. Protocol-Specific Details:
For any selected packet, Wireshark breaks it into layers:
Frame Layer: Capture metadata
Ethernet Layer: Source/destination MAC
IP Layer: Source/destination IP, TTL, checksum
Transport Layer: TCP/UDP ports, flags, sequence numbers
Application Layer: HTTP headers, DNS queries, etc.
