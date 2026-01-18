# Project-05-Dynamic-Routing-with-OSPF
This project connects a branch office to a head office using a point-to-point WAN link and multiple VLANs at the HQ. Static routing is replaced with OSPF (single-area) for dynamic route advertisement. =
# Network Design
- Head Office VLANs:
  - HR – 192.168.10.0/24
  - IT – 192.168.20.0/24
  - Finance – 192.168.30.0/24
- Branch Office LAN – 192.168.40.0/24
- WAN Link – 10.0.0.0/30

# Technologies Used
- Router-on-a-Stick (Inter-VLAN Routing)
- OSPF (Dynamic Routing)
- Point-to-Point WAN
- IPv4 addressing
- End-to-End connectivity verification

# Verification
- OSPF routes visible in routing tables
- Branch PC can ping all HQ PCs across VLANs
- Routers automatically learn new networks without static routes

# Key Learning Outcomes
- Implementing dynamic routing with OSPF
- Understanding OSPF neighbor relationships and route advertisement
- Troubleshooting adjacency and end-to-end connectivity issues
- Replacing static routes with scalable dynamic routing
