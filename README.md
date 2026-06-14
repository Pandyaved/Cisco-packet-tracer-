# LAN Network Setup Using Cisco Packet Tracer

## Project Overview

This project demonstrates a simple Local Area Network (LAN) topology created using Cisco Packet Tracer. The network consists of two PCs connected through a Cisco 2960 switch, with a Cisco 1941 router providing network connectivity and routing capabilities.

## Network Topology

### Devices Used

* Cisco 1941 Router
* Cisco 2960-24TT Switch
* PC0
* PC1

### Connections

* PC0 connected to Switch0
* PC1 connected to Switch0
* Switch0 connected to Router0

## Objectives

* Understand basic network topology design.
* Configure end devices within a LAN.
* Learn switch-to-router connectivity.
* Test network communication between devices.
* Practice Cisco Packet Tracer simulation and configuration.

## Network Configuration

| Device  | Interface          | IP Address  |
| ------- | ------------------ | ----------- |
| PC0     | FastEthernet0      | 192.168.1.2 |
| PC1     | FastEthernet0      | 192.168.1.3 |
| Router0 | GigabitEthernet0/0 | 192.168.1.1 |

Subnet Mask: 255.255.255.0

Default Gateway:

* PC0 → 192.168.1.1
* PC1 → 192.168.1.1

## Testing

* Verified connectivity using ICMP ping.
* Confirmed successful communication between PC0 and PC1.
* Validated router and switch connections.

## Skills Demonstrated

* Network Topology Design
* Cisco Packet Tracer
* Router Configuration
* Switch Configuration
* IP Addressing
* Network Troubleshooting
* LAN Implementation

## Conclusion

This project successfully demonstrates the implementation of a basic LAN using Cisco Packet Tracer. The network allows communication between hosts through a switch and router while showcasing fundamental networking concepts such as IP addressing, routing, and connectivity testing.
