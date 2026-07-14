# 📚 Phase 2 – Computer Networking for VAPT

> **Goal:** Build a strong networking foundation required for VAPT, Penetration Testing, Bug Bounty, SOC, and Red Teaming.

---

# Chapter 1 – Introduction to Computer Networks

## Definition

A **Computer Network** is a collection of two or more devices connected together to communicate, share data, resources, and services using communication protocols.

## Simple Definition

A network is a group of connected devices that can exchange information.

## Example

- Your laptop connects to your home Wi-Fi.
- The Wi-Fi router connects to the Internet.
- You open Google in your browser.
- Your request travels through the network to Google's server.
- Google sends the webpage back to your laptop.

This entire communication happens through a computer network.

---

# Chapter 2 – Types of Networks

## Definition

A network can be classified based on its geographical coverage, purpose, and architecture.

## Example

- PAN → Bluetooth between phone and earbuds
- LAN → Office network
- WLAN → Home Wi-Fi
- MAN → City-wide ISP network
- WAN → Internet
- VPN → Secure connection to a company network

---

# Chapter 3 – Network Devices

## Definition

Network devices are hardware components used to connect, manage, secure, and route network traffic.

## Example

A company network may contain:

- Router
- Switch
- Firewall
- Wireless Access Point
- IDS
- IPS

---

# Chapter 4 – Network Topologies

## Definition

A network topology defines the physical or logical layout of devices within a network.

## Example

Most offices use a **Star Topology**, where every computer connects to a central switch.

---

# Chapter 5 – OSI Model

## Definition

The **OSI (Open Systems Interconnection)** Model is a seven-layer conceptual framework used to understand how data moves across a network.

## Example

When you visit **https://google.com**, your data passes through all seven OSI layers before reaching Google's server.

---

# Chapter 6 – TCP/IP Model

## Definition

The **TCP/IP Model** is the practical networking model used on the Internet. It defines how devices communicate using TCP/IP protocols.

## Example

When you browse a website:

Browser → TCP → IP → Ethernet → Internet

---

# Chapter 7 – Data Encapsulation

## Definition

Data Encapsulation is the process of adding protocol headers (and sometimes trailers) to data as it moves down the networking layers before transmission.

## Example

Application Data

↓

TCP Header

↓

IP Header

↓

Ethernet Header

↓

Frame sent on the network

---

# Chapter 8 – Ethernet

## Definition

Ethernet is the most widely used LAN technology that defines how devices communicate over wired networks.

## Example

Your desktop computer connected to a switch using an Ethernet cable.

---

# Chapter 9 – IPv4 Addressing

## Definition

IPv4 is a 32-bit addressing scheme used to uniquely identify devices on a network.

## Example

192.168.1.10

---

# Chapter 10 – IPv6 Basics

## Definition

IPv6 is a 128-bit addressing system developed to overcome IPv4 address exhaustion.

## Example

2001:db8::1

---

# Chapter 11 – Subnetting

## Definition

Subnetting is the process of dividing a large network into smaller, manageable subnetworks.

## Example

192.168.1.0/24

↓

192.168.1.0/25

192.168.1.128/25

---

# Chapter 12 – MAC Address

## Definition

A MAC Address is a unique 48-bit hardware address assigned to a network interface card (NIC).

## Example

00:1A:2B:3C:4D:5E

---

# Chapter 13 – ARP Protocol

## Definition

ARP (Address Resolution Protocol) maps an IPv4 address to a MAC address on a local network.

## Example

IP Address

192.168.1.10

↓

MAC Address

00:1A:2B:3C:4D:5E

---

# Chapter 14 – DNS

## Definition

DNS (Domain Name System) translates domain names into IP addresses.

## Example

google.com

↓

142.250.x.x

---

# Chapter 15 – DHCP

## Definition

DHCP automatically assigns IP addresses and other network settings to devices.

## Example

When your laptop connects to Wi-Fi, the router automatically assigns it an IP address.

---

# Chapter 16 – NAT

## Definition

NAT (Network Address Translation) converts private IP addresses into public IP addresses for Internet communication.

## Example

192.168.1.10

↓

203.x.x.x

---

# Chapter 17 – Routing

## Definition

Routing is the process of forwarding packets from one network to another using routers.

## Example

Your request travels from your home router to Google's network through multiple routers.

---

# Chapter 18 – Switching

## Definition

Switching is the process of forwarding Ethernet frames within the same local network using MAC addresses.

## Example

PC1 sends data to PC2 through a switch.

---

# Chapter 19 – VLAN

## Definition

A VLAN (Virtual Local Area Network) logically separates devices into different broadcast domains on the same physical switch.

## Example

VLAN 10 → HR Department

VLAN 20 → Finance Department

---

# Chapter 20 – Ports & Services

## Definition

Ports identify specific network services running on a computer.

## Example

80 → HTTP

443 → HTTPS

22 → SSH

3389 → RDP

---

# Chapter 21 – TCP

## Definition

TCP (Transmission Control Protocol) is a reliable, connection-oriented protocol that ensures accurate data delivery.

## Example

Downloading a file from a website.

---

# Chapter 22 – UDP

## Definition

UDP (User Datagram Protocol) is a fast, connectionless protocol that does not guarantee delivery.

## Example

Video streaming

Voice calls

Online gaming

---

# Chapter 23 – Common Network Protocols

## Definition

Network protocols are standardized rules that allow devices to communicate.

## Example

HTTP

HTTPS

FTP

SSH

DNS

SMTP

SNMP

SMB

---

# Chapter 24 – Packet Flow

## Definition

Packet Flow describes the journey of a packet from the source device to the destination.

## Example

Laptop

↓

Switch

↓

Router

↓

Firewall

↓

Internet

↓

Web Server

---

# Chapter 25 – Introduction to Firewalls

## Definition

A Firewall is a security device or software that monitors and controls incoming and outgoing network traffic based on predefined rules.

## Example

A firewall blocks unauthorized access to a company's web server while allowing legitimate users to connect.
