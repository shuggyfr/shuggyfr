## Cybersecurity
#Include tools, programming languages later on


I am a cybersecurity professional with a strong interest in security operations and threat monitoring. Proficient in multiple programming language, I bring analytical skills and attention to detail to the forefront of incident detection and response. I am highly committed to safeguarding information systems, preserving privacy, and ensuring organizational resilience against cyber threats. Within a Security Operations Center environment, I prioritize efficiency, accuracy, and thoroughness—whether triaging alerts, investigating anomalies, or supporting incident response. My goal is to contribute to a proactive defense posture by identifying, analyzing, and mitigating threats in real time.


<!--
**shuggyfr/shuggyfr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

1. Topology Setup
	•	Built the network topology with 3 autonomous systems (AS100, AS200, OSPF Area 1 & Backbone).
	•	Assigned hostnames and IP addresses according to the addressing plan.

📸 Screenshot to include: Full topology view (like the one you uploaded).

⸻

2. OSPF Configuration
	•	Configured R1 and R2 to run OSPF, dividing the network into OSPF Area 1 and the Backbone.
	•	Verified routing tables to confirm OSPF adjacencies.

📸 Screenshot to include: CLI output of show ip ospf neighbor and show ip route ospf.

⸻

3. BGP Configuration
	•	Enabled BGP on R2 and R3 to advertise the 222.223.50.0/24 public network.
	•	Established external BGP sessions between AS100 and AS200.

📸 Screenshot to include: CLI output of show ip bgp summary.

⸻

4. Access Control List (ACL)
	•	Applied ACL to deny all inbound traffic to PC at 192.168.2.1.
	•	Verified ACL rules by testing connectivity before and after ACL deployment.

📸 Screenshot to include: CLI of ACL config (access-list, show access-lists).

⸻

5. DNS & HTTP Server Setup
	•	Configured Server (192.168.1.3) in AS100 with HTTP and DNS services.
	•	Registered domain name: first_lastname.com.
	•	Configured PCs in 192.168.1.0/24 and 192.168.2.0/24 to use the DNS server.

📸 Screenshot to include: Server config window (DNS entries + HTTP service ON).

⸻

6. NAT Configuration
	•	Configured Static NAT on R3 to map server 192.168.1.3 → 222.223.50.3.
	•	Configured NAT overload for outbound traffic from 172.16.0.0/16 to reach the internet.

📸 Screenshot to include: CLI output of NAT config and show ip nat translations.

⸻

7. Testing & Verification
	•	Verified web access by browsing to http://first_lastname.com from different PCs.
	•	Confirmed DNS resolution and NAT translation.

📸 Screenshot to include: PC Web Browser window showing server page loading successfully.
