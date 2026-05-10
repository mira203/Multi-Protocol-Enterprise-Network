Enterprise Network Design with Multi-Protocol Routing

●  Project Overview
This project demonstrates the design and configuration of a complex enterprise network using Cisco Packet Tracer. The topology connects multiple regional offices (Cairo, Alex, Damietta, Giza) through a Frame Relay Cloud, ensuring seamless connectivity across different routing domains.

<img width="1368" height="691" alt="image" src="https://github.com/user-attachments/assets/519a5020-02bb-476a-bf21-ceb95fd59101" />


●  Key Features
Multi-Protocol Integration: Implementation of OSPF, EIGRP (AS 5 & 6), and RIP protocols.

Route Redistribution: Successfully configured mutual redistribution between OSPF, EIGRP, and RIP to ensure full network reachability.

WAN Technologies: Configured Frame Relay with sub-interfaces and DLCI mapping for different branches.

VLAN Management: Implemented VLAN 10 and VLAN 20 for departmental segmentation.

Addressing Scheme: Systematic IP addressing using both Classful and Classless (VLSM) strategies.

● Topology Details
The network consists of:

Core Cloud: Frame Relay connecting various routers.

Routing Domains: * OSPF domain for internal high-speed routing.

EIGRP domains for scalable enterprise routing.

RIP for legacy system simulation.

End Devices: PCs distributed across different subnets (192.168.x.x, 70.0.0.x, etc.) to verify end-to-end connectivity via Ping and Traceroute.

● How to Run
Download the .pkt file from this repository.

Open it using Cisco Packet Tracer (v8.0 or higher recommended).

Wait for the convergence of routing protocols.

Test connectivity by pinging between PC0 and PC13.
