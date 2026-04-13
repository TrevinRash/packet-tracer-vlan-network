# VLAN Network Project (Packet Tracer)

## Overview

Designed and implemented a small business network using VLAN segmentation and inter-VLAN routing.

## Objectives

* Configure VLANs for department separation (HR, Sales, IT)
* Enable inter-VLAN communication using router-on-a-stick
* Implement trunk links between switches
* Perform network troubleshooting and validation

## Network Design

* 2 Switches (2960)
* 1 Router (2911)
* 6 PCs across 3 VLANs

## Technologies Used

* VLANs (802.1Q)
* Inter-VLAN Routing
* Cisco CLI
* Packet Tracer

## IP Scheme

| VLAN       | Network         | Gateway      |
| ---------- | --------------- | ------------ |
| 10 (HR)    | 192.168.10.0/24 | 192.168.10.1 |
| 20 (Sales) | 192.168.20.0/24 | 192.168.20.1 |
| 30 (IT)    | 192.168.30.0/24 | 192.168.30.1 |

## Testing

* Verified intra-VLAN connectivity
* Verified inter-VLAN routing via router
* Troubleshot VLAN and trunk issues

## Files Included

* Packet Tracer file (.pkt)
* Device configurations
* Network topology diagram
