# Market-Network-Design-Project
A complete network infrastructure design for a small-to-mid-sized market or shopping complex. Includes VLAN segmentation, secure guest Wi-Fi, CCTV/IP camera setup, POS system integration, firewall rules, and monitoring layout. Config files, simulation placeholders, and topology diagrams included for deployment or academic portfolio use
Overview

Design and simulate a network for a multi-shop market with:

Central admin office

10–20 individual retail stores

Guest Wi-Fi

CCTV and IoT integration

POS (Point-of-Sale) systems

Internet + Local communication



---

# **Key Features**

Topology: Star or Hybrid (Main switch/router connects to store switches)

Connectivity:

Wired LAN for shop POS, PCs, IP cameras

Wi-Fi for guests and mobile POS terminals


IP Schema:

Admin: 192.168.10.0/24

Stores: 192.168.20.0/24

CCTV: 192.168.30.0/24

Guest Wi-Fi: 192.168.50.0/24


Security:

VLANs per function

Firewall & ACLs between shop VLANs

Secure Wi-Fi (WPA3), VPN for admin access


Monitoring:

Bandwidth usage via SNMP (Zabbix/PRTG)

Central syslog and alerts




---

# **Network Devices Used**

Routers (1)

Layer 3 Switch (1)

Layer 2 Switches (per floor/row)

Access Points (dual-band)

IP Cameras

POS Terminals



---

# **Simulation Tools**

Cisco Packet Tracer or GNS3

Draw.io for diagrams

Wireshark for packet capture

Zabbix/PRTG for monitoring setup



---

# **Project Folder Structure**

/market-network-design
├── diagrams/
│   └── market-topology.png
├── simulation/
│   └── market-network.pkt
├── config-scripts/
│   ├── router-config.txt
│   ├── switch-configs/
│   └── firewall-rules.txt
├── documentation/
│   └── design-report.pdf
└── README.md
