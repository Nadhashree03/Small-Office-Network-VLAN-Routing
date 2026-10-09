# Small Office Network using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the basic design of a small office network using Cisco Packet Tracer. It consists of four PCs, one switch, and one router. The project focuses on network topology, IP address configuration, VLAN creation, and basic connectivity testing.

## 🎯 Aim

To design a small office network using Cisco Packet Tracer and understand basic IP addressing, VLAN configuration, and network connectivity.

## 🛠️ Tools Used

* Cisco Packet Tracer
* PCs
* Cisco Switch
* Cisco Router
* Copper Straight-Through Cables

## 🖥️ Network Topology

The network contains:

* 4 PCs
* 1 Switch
* 1 Router

All four PCs are connected to the switch, and the switch is connected to the router.

## 🌐 IP Address Configuration

| Device | IP Address    | Subnet Mask   |
| ------ | ------------- | ------------- |
| PC0    | 192.168.10.10 | 255.255.255.0 |
| PC1    | 192.168.10.11 | 255.255.255.0 |
| PC2    | 192.168.20.10 | 255.255.255.0 |
| PC3    | 192.168.20.11 | 255.255.255.0 |

## 🔀 VLAN Configuration

Two VLANs were created to separate the PCs into different logical groups.

* **VLAN 10 — HR:** PC0 and PC1
* **VLAN 20 — Sales:** PC2 and PC3

Switch ports were assigned to their respective VLANs.

## 🧪 Connectivity Testing

The `ping` command was used to test connectivity between PCs in the same VLAN.

* PC0 to PC1: Tested
* PC2 to PC3: Tested
* Communication between different VLANs requires inter-VLAN routing configuration.

## 📚 Learning Outcomes

* Understanding basic network topology.
* Configuring IPv4 addresses and subnet masks.
* Creating VLANs on a switch.
* Assigning switch ports to VLANs.
* Testing basic network connectivity using `ping`.

## 📁 Project File

**File:** `Small_Office_Network.pkt`

Open the project file using Cisco Packet Tracer to view the network topology and configuration.

## ✅ Conclusion

The small office network was designed using Cisco Packet Tracer. IP addressing and VLAN configuration were performed, and basic connectivity testing was carried out to understand the fundamentals of computer networking.
