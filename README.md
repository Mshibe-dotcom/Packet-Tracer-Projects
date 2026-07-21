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
<image-card alt="Basic Connectivity Topology" src="topology.png" ></image-card>

**PC2:**
- IP Address: `192.168.1.10`
- Subnet Mask: `255.255.255.0`
- Default Gateway: (not needed for direct connection)
  **PC3:**
- IP Address: `192.168.1.11`
- Subnet Mask: `255.255.255.0`
  
  ## Testing & Verification
![Ping Test](ping-test.png)
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
![Star Topology](star.png)

## Configuration
**IP Addresses:**
-PC0: '192.168.1.2'
-PC3: '192.168.1.3'
-PC4: '192.168.1.1'
-PC5: '192.168.1.4'

## Testing Verification
![Ping Test](ping.png)
All devices can communicate successfully.

## Skills Demonstrated
- Star topology design
- Switch configuration basics
- Ethernet cabling (straight-through)
- Multi-device IP addressing & subnetting
- Network testing and verification

##Key Learnings
A switch creates a star topology where all devices connect centrally. Unlike a simple peer-to-peer connection, this allows scalable LAN communication. All devices must be in the same subnet for direct communication without a router.
