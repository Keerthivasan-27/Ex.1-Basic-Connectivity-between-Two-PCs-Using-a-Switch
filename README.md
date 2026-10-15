## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	15/10/2026	
KEERTHIVASAN A  BE ECE 4TH YEAR (212223060124)
# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1917" height="1077" alt="Screenshot 2026-10-15 162029" src="https://github.com/user-attachments/assets/d2644c23-f8d4-400d-ba0d-52aff5c50642" />


________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1917" height="1078" alt="Screenshot 2026-10-15 162757" src="https://github.com/user-attachments/assets/21ab2528-5d88-44ac-b8b1-aea7ddd4f9f3" />
<img width="1917" height="1078" alt="Screenshot 2026-10-15 215907" src="https://github.com/user-attachments/assets/f1819218-0001-4f07-a139-dbdbbecb4f2b" />
<img width="1915" height="1073" alt="image" src="https://github.com/user-attachments/assets/e0bb4540-39cb-467c-b6da-7753463f8559" />

<img width="1917" height="1078" alt="Screenshot 2026-10-15 220038" src="https://github.com/user-attachments/assets/d87e43a4-84b3-4e2b-a0d1-85b677bb7f21" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
