# TechCorp Networking Lab Write-Up

## Introduction

Scenario: "You're building the network for a fictional company — TechCorp — with a headquarters site, a branch site, and a DMZ hosting a public-facing server. Everything interconnects over a simulated internet."

Topology of the network reproduced in GNS3: (TODO)

Addressing table availble [here](./addressing-table.md).

## Stage 01: Base Device Configuration 

### Objective

Configure common settings and secure access to all devices. Additionally, enable management and logging capabilities for easier troubleshooting.

### Tasks

- Disable CDP on WAN-facing interfaces, IP domain-lookup, HTTP server
- Set hostnames, domain name, MOTD and login banners
- Set privileged access mode password and enable passowrd encryption
- Generate 2048-bit RSA keys and create an administrative user in the local database 
- Configure SSH(v2 only) on all VTY lines, console and aux port hardening, exec-timeout
- Configure NTP hierarchy — ISP-SIM as source, everything else - client
- Enable Syslog to management VLAN PC
- Configure SNMPv3 authPriv
- Set interface descriptions on every used port
- Set login block-for,

### Scope

Devices Affected:

- HQ-AS
- HQ-DS
- HQ-FW
- HQ-ER
- ISP-SIM
- BR-ER
- BR-DS
- BR-AS

### Configuration


### Verification

### Issues Encountered
