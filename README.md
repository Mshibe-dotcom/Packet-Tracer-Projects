# Cisco Packet Tracer Projects
Hands-on networking labs from fundamentals to advanced topics.

## Skills Demonstrated
- Networking Fundamentals
- Cisco Packet Tracer
- ...

More projects coming soon!

# Project 01: Basic Connectivity (Two PCs)

# Overview
Implemented a simple peer-to-peer network using two PCs connected via Ethernet in Cisco Packet Tracer. This project demonstrates fundamental networking concepts: cabling, IP addressing, and connectivity testing.

# Objectives
- Understand straight-through vs crossover cabling
- Configure static IPv4 addresses
- Verify connectivity using ICMP ping
  
# Topology
![Basic Connectivity Topology](Basic%20Connectivity/topology.png)
**PC2:**
- IP Address: `192.168.1.10`
- Subnet Mask: `255.255.255.0`
- Default Gateway: (not needed for direct connection)
  **PC3:**
- IP Address: `192.168.1.11`
- Subnet Mask: `255.255.255.0`
  
  ## Testing & Verification
![Basic Connectivity Topology](Basic%20Connectivity/PC2-Ping-Testing.png)
Successful communication between devices confirmed.

## Skills Demonstrated
- Network device placement in Packet Tracer
- Proper Ethernet cabling selection
- IPv4 addressing and subnetting basics
- Basic troubleshooting (link lights, ping)
  
## Key Learnings
This project reinforced the importance of matching cable types and correct IP configuration in the same subnet for direct device communication.

# Project 02:Star Topology(one switch and four PCs)

## Overview
Built a basic local Area Network(LAN) using a central switch conneting multiple end devices. Ths demonstrate how switches handle traffic in a star topology.

## Objectives
-Create a star topology in Cisco Packet Tracer
-Configure multiple devices with static IPv4 addresses
-Verify full connectivity using ping

## Topology
![Star Topology](Star%20Topology/Star-Topology.png)

*4 PCs connected to a central Switch in star topology.*

## Configuration
**IP Addresses:**
-PC0: '192.168.1.2'
-PC3: '192.168.1.3'
-PC4: '192.168.1.1'
-PC5: '192.168.1.4'

## Testing Verification
![Star Topology](Star%20Topology/PC4-Ping-testing.png)
![Star Topology](Star%20Topology/PC0-Ping-testing.png)
All devices can communicate successfully.

## Skills Demonstrated
- Star topology design
- Switch configuration basics
- Ethernet cabling (straight-through)
- Multi-device IP addressing & subnetting
- Network testing and verification

##Key Learnings
A switch creates a star topology where all devices connect centrally. Unlike a simple peer-to-peer connection, this allows scalable LAN communication. All devices must be in the same subnet for direct communication without a router.

# Project 03: Simple Router Network(One Router,Two Switches,Four PCs)

## Overview
Connected two separate LANs using a router to enable inter-network communication.

## Topology
![Simple Router Network](Simple%20Router%20Network/Simple-Router-Topology.png)

## Configuration
**LAN 1 (192.168.1.0/24)**
- Router G0/0/0: 192.168.1.3
- PCs: 192.168.1.1, 192.168.1.2

**LAN 2 (192.168.2.0/24)**
-Router G0/0/1: 192.168.2.3
-PCs: 192.168.2.1, 192.168.2.2

## Router CLI (Key Commands)
![Simple Router Network](Simple%20Router%20Network/Router-Commands.png)

## Testing
![Simple Router Network](Simple%20Router%20Network/PC0-PC2-PDU-Simulation.png)

## PC1 Ping PC2
![Simple Router Network](Simple%20Router%20Network/PC1-Ping.png)
## Skills Demonstrated
- Router interface configuration
- Inter-VLAN / Inter-subnet routing
- Static routing basics
- End-to-End network troubleshooting


