# Enterprise-network-construction

## VLAN Configuration:
### Port Segmentation:

### Configuring VLAN IP Addresses
```shell
interface GigabitEthernet 0/0/1
```
### Allowing VLANs to Pass
```shell
port trunk allow-pass vlan all
```
# Port Types
Trunk
Trunk ports are used for VLAN communication between switches. Data packets passing through Trunk ports are tagged with VLAN labels, allowing network isolation.

Access
Access ports are used for VLAN communication between computers and switches.

OSPF Dynamic Routing Configuration
Creating OSPF Routes
Creating OSPF Areas
Configuring Area Networks
Displaying Routing Table

VLAN Segmentation: Trunk ports are used between switches.
VLAN Creation: interface Eth-Trunk 1
Port Segmentation: interface GigabitEthernet 0/0/1
Configuration of VLAN IP: ip address 192.168.1.12 255.255.255.0
Allowed VLANs to Pass: port trunk allow-pass vlan all

Port Types: Trunk, Access
Trunk: Used for VLANs, which means that data packets between switches, passing through Trunk ports, will be tagged with VLAN labels. This allows switches to isolate networks using these labels.
Access: Used for VLANs, which means for communication between computers and switches.

OSPF Dynamic Routing Configuration:
Creating OSPF Route: ospf 100
Creating OSPF Area: area 0
Configuring Area Networks: network 192.168.200.0 255.255.255.0
Displaying Routing Table: display ip routing-table




