# Enterprise Network Project Documentation

## Topology Overview
[Include your topology diagram]

## IP Addressing Scheme

| Device | Interface | IP Address | VLAN |
|--------|-----------|------------|------|
| HQ-Dist-SW1 | VLAN 10 | 10.10.10.2/24 | Management |
| HQ-Dist-SW1 | VLAN 20 | 10.10.20.2/24 | Users |
| HQ-Dist-SW1 | VLAN 30 | 10.10.30.2/24 | Voice |
| HQ-Dist-SW2 | VLAN 10 | 10.10.10.3/24 | Management |
| HQ-Dist-SW2 | VLAN 20 | 10.10.20.3/24 | Users |
| HQ-Dist-SW2 | VLAN 30 | 10.10.30.3/24 | Voice |
| HQ-Core-Router | G0/0 | 172.16.1.1/30 | - |
| HQ-Core-Router | G0/1 | 172.16.1.5/30 | - |
| DC-Router | G0/0 | 10.10.100.1/24 | Server |
| Branch-Internal | G0/0 | 192.168.1.1/24 | Branch LAN |

## Technologies Implemented
- VLANs with Port Security
- EtherChannel (LACP)
- HSRP for gateway redundancy
- Multi-area OSPF
- GRE over IPSec VPN
- DHCP with relay
- DNS services
- AAA with RADIUS
- Extended ACLs
- Python automation

## Testing Results
[Include screenshots of successful tests]