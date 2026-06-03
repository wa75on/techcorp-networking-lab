| Segment      | Network          | Description                                               |
| :----------: | :--------------: | :-------------------------------------------------------: |
| ISP-SIM Lo0  | 100.64.0.1/24    | Simulated internet                                        |
| HQ - ISP-SIM | 203.0.113.0/30   | HQ WAN link to ISP                                        |
| BR - ISP-SIM | 203.0.113.4/30   | BR WAN link to ISP                                        |
| GRE HQ - BR  | 10.0.0.0/30      | Tunnel overlay between HQ and BR                          |
| HQ VLAN 10   | 192.168.10.0/24  | HQ "SALES" VLAN for hosts in the Sales sector of TechCorp |
| HQ VLAN 20   | 192.168.20.0/24  | HQ "IT" VLAN for hosts in the IT sector of TechCorp       |
| HQ VLAN 30   | 192.168.30.0/24  | HQ "MGMT" VLAN for network administrators of TechCorp     |
| BR VLAN 10   | 192.168.110.0/24 | BR "SALES" VLAN for hosts in the Sales sector of TechCorp |
| BR VLAN 20   | 192.168.120.0/24 | BR "IT" VLAN for hosts in the IT sector of TechCorp       |
| BR VLAN 30   | 192.168.130.0/24 | BR "MGMT" VLAN for network administrators of TechCorp     |
