# VLAN-Based-College-Network
A VLAN-based college network designed and configured in Cisco Packet Tracer. The project demonstrates VLAN segmentation for different departments, trunking between devices, and inter-VLAN communication using Router-on-a-Stick. It includes IP addressing, default gateway configuration, and connectivity testing between VLANs.
# College VLAN Network Project

This project demonstrates VLAN segmentation and inter-VLAN routing using Cisco Packet Tracer.

# Network Design
Departments:
- Admin (VLAN 10)
- Library (VLAN 20)
- CS (VLAN 30)
- ECE (VLAN 40)

Each department has 2 computers connected to a switch.

# Technologies Used
- Cisco Packet Tracer
- VLAN Configuration
- Trunking
- Router-on-a-Stick
- Inter-VLAN Routing

# IP Addressing

Admin: 192.168.10.0/24  
Library: 192.168.20.0/24  
CS: 192.168.30.0/24  
ECE: 192.168.40.0/24  

# Router Configuration
Router subinterfaces were used to enable communication between VLANs.

## Simulation
Packet Tracer simulation mode was used to verify packet flow between VLANs.
