
# Week 04 - Internship 

## Topic Studied
### Enterprise Network Design Using Core, Distribution, and Access Layers

During the fourth week of my Network Security internship at Cyberster, I designed and implemented a hierarchical enterprise network using Cisco Packet Tracer. The network was built following the **Core, Distribution, and Access Layer** architecture to understand scalable and efficient enterprise network design. Three routers were configured as the Core Layer using OSPF dynamic routing, while switches connected end devices and servers to provide network services. :contentReference[oaicite:0]{index=0}

---

## Network Architecture

The enterprise network included:

- 3 Cisco 2811 Routers (Core Layer)
- 3 Cisco 2960 Switches (Distribution Layer)
- Multiple Client PCs (Access Layer)
- 2 Servers
- OSPF Area 0 for dynamic routing

---

## Core Layer

- Configured three routers as the backbone of the network.
- Connected routers in a triangular topology.
- Implemented OSPF Area 0 for dynamic route exchange.
- Verified OSPF neighbor relationships.
- Checked routing tables and routing protocols.

### Skills Learned

- OSPF Configuration
- Router Configuration
- Dynamic Routing
- Routing Verification
- Enterprise Backbone Design

---

## Distribution Layer

- Connected each router to a Cisco 2960 switch.
- Aggregated traffic from access networks.
- Forwarded packets between the Core Layer and Access Layer.

### Skills Learned

- Switch Configuration
- Traffic Aggregation
- Network Distribution

---

## Access Layer

- Connected client PCs and servers to switches.
- Configured static IP addresses and default gateways.
- Enabled communication between users and network services.

### Skills Learned

- End Device Configuration
- IP Addressing
- Gateway Configuration

---

## Server Configuration

Two servers were added to the network to provide centralized services.

The servers were configured with:

- Static IP Address
- Subnet Mask
- Default Gateway

Client PCs successfully accessed server resources through the routed network. :contentReference[oaicite:1]{index=1}

---

## Connectivity Verification

The following tests were successfully performed:

- OSPF Neighbor Verification
- Routing Table Verification
- Show IP Protocols
- End-to-End Ping Tests
- Client-to-Server Connectivity
- Web Service Access from Client PCs

---

## Layer Responsibilities

### Core Layer
- Provides high-speed routing between different networks.
- Forms the backbone of the enterprise network.

### Distribution Layer
- Connects the Core Layer to access switches.
- Aggregates traffic and forwards packets efficiently.

### Access Layer
- Connects end-user devices such as PCs and servers.
- Provides users with access to network resources.

---

## Learning Outcomes

- Understood hierarchical enterprise network architecture.
- Configured and verified OSPF dynamic routing.
- Designed networks using Core, Distribution, and Access Layers.
- Configured routers, switches, servers, and client devices.
- Verified end-to-end connectivity and routing information.
- Improved troubleshooting and enterprise networking skills. :contentReference[oaicite:2]{index=2}

---

## Tools Used

- Cisco Packet Tracer
- Cisco 2811 Routers
- Cisco 2960 Switches
- OSPF Routing Protocol
- PCs
- Server-PT

---

## Conclusion

This task provided practical experience in designing a scalable enterprise network using the Core, Distribution, and Access Layer model. By configuring three routers with OSPF, connecting two servers, and verifying communication between all devices, I gained a deeper understanding of enterprise networking concepts and hierarchical network design. :contentReference[oaicite:3]{index=3}
