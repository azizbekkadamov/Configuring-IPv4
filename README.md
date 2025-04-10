# 🛰️ Configuring IPv4 Static Routes (Cisco Packet Tracer Project)

This project focuses on implementing static routing in a small network using **Cisco Packet Tracer**. Static routing is one of the most fundamental networking concepts and is critical for understanding how routers make forwarding decisions without dynamic protocols.

This lab demonstrates how to manually configure IPv4 static routes and basic router settings to enable full communication across a simple network topology.

---

## 🧱 Project Overview

The lab is broken down into two main parts:

1. **Basic Router Configuration**
   - Naming devices based on the given topology
   - Disabling DNS lookups
   - Setting console, VTY, and enable passwords
   - Creating a local user with custom credentials

2. **Static Routing**
   - Manually adding IPv4 static routes to enable inter-router communication
   - Testing connectivity between PCs across networks
   - Saving the configuration to NVRAM

---

## 🖧 Network Topology

The topology consists of multiple routers and hosts, each assigned a specific IP configuration. While the visual diagram is included in the `.pkt` file, here’s a general layout:

- **Multiple routers** connected serially or via Ethernet interfaces.
- **PCs or endpoints** connected to each router’s local network.
- Static routes are added to allow each router to know how to reach networks beyond its directly connected interfaces.

---

## 🔐 Configuration Details

### Router Settings:
- **Enable password**: `class`
- **Console password**: `cisco`
- **VTY password**: `cisco`
- **Local user account**:
  - **Username**: `Your_Name`  
  - **Password**: `Student_ID`

### Routing:
- Static routes are configured on each router using the `ip route` command.
- Each router has manually defined paths to reach non-directly connected networks.

---

## 💾 Files Included

- `Configuring IPv4.pkt` — Complete Packet Tracer project file.
- `README.md` — Full documentation and setup instructions.

---

## 🚀 How to Use This Project

1. Open the `.pkt` file using **Cisco Packet Tracer**.
2. Click on routers to view interface configurations and routing tables.
3. Use the `ping` command on PCs to test inter-network connectivity.
4. Examine static routes using the `show ip route` and `show running-config` commands.

---

## 🎓 Learning Outcomes

By completing this lab, you will:
- Understand how to configure and verify static routes.
- Learn to structure basic router setup with secure access credentials.
- Improve CLI skills in navigating router configs and troubleshooting.
- See how routers handle traffic between non-directly connected networks.

---

## 🛠️ Tools Used

- **Cisco Packet Tracer**
- **Cisco IOS CLI**

---

## 📌 Notes

This project was submitted as part of a networking lab focused on static routing. It includes all required configurations and has been fully tested in Packet Tracer. The `.pkt` file is named according to the assignment instructions for identification and submission purposes.
