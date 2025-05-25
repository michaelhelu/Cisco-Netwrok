# Cisco Network Simulation – Packet Tracer Project

This is a Cisco Packet Tracer (.pkt) simulation project designed to practice and demonstrate core networking concepts including VLANs, inter-VLAN routing (Router-on-a-Stick), RIP routing protocol, SSH configuration, SYSLOG server setup, and WAN connectivity via a gateway of last resort.

## 🧰 Features

- VLANs: VLAN 10, 20, and 30 implemented across multiple switches
- Inter-VLAN Routing: Router-on-a-Stick setup on Router0 and Router1
- RIP (Routing Information Protocol): Used for dynamic routing between routers
- SSH: Secure remote access configured on all switches
- SYSLOG Server: Centralized log server connected and tested
- Gateway of Last Resort: WAN configuration with a static default route on Router1

## 🖧 Devices Used

- Multiple Switches (SW-A, SW-B, SW-C, SW-D)
- Two Routers (Router0 and Router1)
- End devices (PCs and Servers)
- One SYSLOG Server
- One WAN Router connected to Router1

## 🔐 Security

- SSH access is enabled on all switches
- Local login credentials set (username/password)
- Encrypted passwords using `service password-encryption`

## 📂 Files

- `Cisco-Network-Project.pkt` — The main Packet Tracer simulation file

## ✅ How to Use

1. Open the `.pkt` file using Cisco Packet Tracer (version 8.2 or higher recommended)
2. View configurations on routers and switches (especially RIP, VLANs, SSH, SYSLOG)
3. Test:
   - VLAN isolation and inter-VLAN routing
   - SYSLOG server logging events
   - SSH remote login using the command line (e.g., `ssh -l admin 192.168.x.x`)
   - Internet reachability via WAN (e.g., ping 8.8.8.8 from inside)

## 📷 Screenshot
(https://github.com/user-attachments/assets/89e69555-8f0e-4dee-8b72-62bef8ffb992)

---

Feel free to clone, study, and use this simulation for your learning or teaching purposes.
