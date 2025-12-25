# Cisco Packet Tracer – RIP v2 Multi-Router Topology

This project contains a Cisco Packet Tracer lab where I configured a network with **3 routers**, switches, and end-devices across multiple subnets. RIP v2 dynamic routing was implemented to enable end-to-end connectivity.

## 🚀 What’s Included
- Packet Tracer `.pkt` file – full working topology
- Router configurations (show ip route, show ip int brief)
- Ping test verification for successful connectivity

## 🧰 Technologies Used
- Cisco Packet Tracer
- RIP v2 Dynamic Routing
- IPv4 Subnetting
- Router CLI Configuration
- ICMP Testing (Ping)

## 🔧 Network Summary
Subnets:
- 192.168.1.0/24
- 192.168.2.0/24
- 192.168.3.0/24
- 192.168.4.0/24
- 192.168.5.0/24

Routers:
- R1 – 192.168.1.100, 192.168.4.1
- R2 – 192.168.4.2, 192.168.2.100, 192.168.5.1
- R3 – 192.168.5.2, 192.168.3.100

## 🧪 Lab Output
- Successful ping from PC in 192.168.1.x to 192.168.3.x
- RIP routing table populated dynamically
- All networks fully reachable

## Lab References

- [Network Topology Diagram](topology.jpeg)

### Router Configuration Screenshots
- [R1 Configuration](R1-config.jpeg)
- [R2 Configuration](R2-config.jpeg)
- [R3 Configuration](R3-config.jpeg)
- 
## 📚 How to Run
1. Download the `.pkt` file from this repo
2. Open in Cisco Packet Tracer
3. Check router CLI using:
