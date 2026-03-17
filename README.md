# Introduction of My Lab Environment

## Overview

The environment is built on a Dell T430 tower server hosting both VMware ESXi 6.5 and an EVE-NG Community Edition virtual machine. Each platform uses its own virtual network adapter, with ESXi assigned 192.168.137.111/24 and EVE-NG assigned 192.168.137.10/24. A management laptop, connected through the same wired network and configured with IP 192.168.137.1/24, provides direct access to both the ESXi hypervisor and the EVE-NG instance for system administration and lab management.

---

## Topology

![Lab Topology](Lab%20Environment/topology.png)

### Network Design

- Spine-leaf Clos architecture
- Layer 3 underlay network
- VXLAN overlay network
- EVPN control plane using BGP
- Anycast gateway for distributed routing

---

## Lab Environment

| Component | Platform |
|---|---|
| Network Emulator | EVE-NG |
| Switch OS | Cisco Nexus 9000v |
| Routing Protocol | OSPF |
| Control Plane | BGP EVPN |
| Overlay Technology | VXLAN |

---

## Topology Structure
# My-Lab-Environment
