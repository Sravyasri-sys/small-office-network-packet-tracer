# small-office-network-packet-tracer
Small office network built and tested in Cisco Packet Tracer

## Overview

This project demonstrates the design and configuration of a small office network using Cisco Packet Tracer.

The network consists of a Cisco router, a Layer 2 switch, three client PCs and a server.

## Network Topology

- 1 × Cisco 2911 Router
- 1 × Cisco 2960-24TT Switch
- 3 × PCs
- 1 × Server

### Network Structure

## IPv4 Addressing

| Device | IPv4 Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| Router0 | 192.168.1.1 | 255.255.255.0 | — |
| PC0 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC1 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.12 | 255.255.255.0 | 192.168.1.1 |
| Server0 | 192.168.1.20 | 255.255.255.0 | 192.168.1.1 |
## Configuration

The following networking concepts were practiced:

- IPv4 addressing
- Subnet masks
- Default gateway configuration
- Router and switch connectivity
- Basic LAN design
- Static IP configuration
- Network connectivity testing

## Testing

Connectivity was tested using `ping`.

Examples:

- PC0 → Router0
- PC1 → PC0
- PC2 → PC0
- PC0 → Server0

All tested connections returned successful replies with **0% packet loss**.

## Tools

- Cisco Packet Tracer
- IPv4
- ICMP / ping

## What I Learned

Through this project I practiced building a basic LAN, configuring IPv4 addresses, connecting network devices and troubleshooting connectivity problems.

This project is part of my practical preparation for an Ausbildung as **Fachinformatikerin für Systemintegration (FISI)**.

## Project File

