# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark
Cyber Security 

1) Open wireshark and go to eth0

   <img width="665" height="171" alt="Image" src="https://github.com/user-attachments/assets/3b6966f0-7283-493b-bd0d-07f0dc30d25c" />

2) Send a ping to google.com

  <img width="689" height="284" alt="Image" src="https://github.com/user-attachments/assets/34777cc7-8f4a-4b5e-8815-7c2f9221f511" /> 

3) Analyse wireshark results

   Protocols

   DNS
   
  <img width="962" height="295" alt="Image" src="https://github.com/user-attachments/assets/22878ee7-d83d-4753-bbec-930d2289e66a" />
   
   ICMP
   
  <img width="1302" height="292" alt="Image" src="https://github.com/user-attachments/assets/be8cbccb-01ca-4969-9483-21c67535da2e" />
  
   ARP
  
  <img width="1254" height="403" alt="Image" src="https://github.com/user-attachments/assets/c5cf31e4-4f68-4ecf-9e51-7561a1a7d343" />
    
  **Questions**

1. **What is Wireshark used for?**
   Wireshark is a network protocol analyzer used to capture, inspect, and analyze network traffic in real time. It helps identify what data is flowing through the network, which protocols are being used, and can diagnose network issues or detect suspicious activity.

2. **What is a packet?**
   A packet is a small unit of data transmitted over a network. It contains a header (with routing and protocol information) and a payload (the actual data being sent). Networks transfer data in packets so it can be efficiently sent and reassembled at the destination.

3. **How to filter packets in Wireshark?**
   Wireshark provides a display filter bar at the top. You can filter packets by typing protocol names or expressions such as `http`, `dns`, `tcp`, or `icmp`.

4. **What is the difference between TCP and UDP?**
   TCP (Transmission Control Protocol) is connection-oriented, ensures reliable delivery, and uses acknowledgments and retransmissions. UDP (User Datagram Protocol) is connectionless, faster, but does not guarantee delivery or order.

5. **What is a DNS query packet?**
   A DNS query packet is sent from a client to a DNS server to resolve a domain name (like google.com) into its corresponding IP address.

6. **How can packet capture help in troubleshooting?**
   Packet capture helps identify where communication is failing, detect latency, dropped packets, misconfigurations, or malicious traffic by showing what is actually being transmitted across the network.

7. **What is a protocol?**
   A protocol is a set of rules that define how data is transmitted and received over a network, ensuring devices communicate correctly (e.g., TCP, HTTP, DNS).

8. **Can Wireshark decrypt encrypted traffic?**
   Wireshark cannot normally decrypt encrypted traffic like HTTPS or SSH unless you have the appropriate decryption keys or use specific debugging setups that provide session keys.
