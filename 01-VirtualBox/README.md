 Chapter 1 - Virtual Machine Configuration

## Objective

Create the virtual infrastructure that will host the Active Directory lab.

## Software Used

- Oracle VirtualBox
- Windows Server 2025 ISO
- Windows 11 Pro ISO

## Virtual Machines

### DC01

- Windows Server 2025 Standard (Desktop Experience)
- 4 GB RAM
- 2 CPU Cores
- 80 GB Dynamic VDI

Networking

- Adapter 1: NAT
- Adapter 2: Internal Network (HOMELAB)

### PC01

- Windows 11 Pro
- 4 GB RAM
- 2 CPU Cores
- 64 GB Dynamic VDI

Networking

- Adapter 1: Internal Network (HOMELAB)

## Screenshots

### DC01 Hardware Configuration

![DC01 Settings](DC01CPU.png) 
![DC01 Settings](DC01Ram.png) 
![DC01 Settings](DC01Storage.png)

### DC01 Network Adapters

![DC01 Network](DC01NETADP1.png)
![DC01 Network 2 ](DC01NETADP2.png)

### PC01 Network Adapter

![PC01 Network](PC01NETADP.png)

## Skills Demonstrated

- Virtual machine creation
- Virtual networking
- Hardware resource allocation
- Network segmentation
