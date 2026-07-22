## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 22/07/2026

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/64b5bd7a-b29c-4f9a-be5a-5c02b49344cb" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.0.1	255.255.255.0
PC1	NIC	192.168.0.2	255.255.255.0
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

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/64fa5e3d-01db-41ec-8a41-9451b0dc4f07" />
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/3be770a1-7fa2-49b6-9996-4849a3bc0895" />



________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
