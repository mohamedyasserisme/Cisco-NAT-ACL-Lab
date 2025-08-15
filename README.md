# Cisco Packet Tracer – NAT (Static, Dynamic, PAT) with ACL

## 📌 Project Overview
This project demonstrates configuring Static NAT, Dynamic NAT, and PAT on a single LAN network, along with Access Control Lists (ACLs) to enforce security rules.

## 🖥️ Topology
- Multiple servers and clients connected to a single LAN.
- NAT-enabled router connected to an ISP.
- ACLs applied for traffic filtering and ICMP blocking.

## 🔧 Configuration Details
### Static NAT Mappings
- 192.168.1.100 ⇔ 100.100.100.100
- 192.168.1.200 ⇔ 200.200.200.200
- 192.168.1.90 ⇔ 90.90.90.90
- 192.168.1.80 ⇔ 80.80.80.80

### Security Policies (ACLs)
- Block all traffic from Server 200 to the internet via ISP1 for User 1.
- Block ICMP Echo Requests and Echo Replies from Internet User 1 to Server 200.

## 📋 Testing & Verification
Commands used:


show ip nat translations
ping 8.8.8.8
ping 200.200.200.200
show access-lists


## 🛠 Tools & Technologies
- Cisco Packet Tracer
- NAT (Static, Dynamic, PAT)
- ACL (Extended)
- Networking CLI Commands

## 📷 Demo
<img width="1851" height="665" alt="Screenshot 2025-08-15 164721" src="https://github.com/user-attachments/assets/cc07f365-8bb7-4a14-9722-6b07c53ea8f1" />
