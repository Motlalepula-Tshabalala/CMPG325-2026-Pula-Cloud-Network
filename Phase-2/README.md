# Phase 2 – Client Implementation Review

## Project
CMPG325-2026-146

## Client
Pula Cloud Services (Kimberley)

## Phase 2 Requirements
1. Working Packet Tracer file
2. Assigned feature implemented
3. Testing evidence
4. Updated GitHub portfolio

## Implementation

The Phase 2 network implementation includes:

- VLAN 10 – Staff
- VLAN 20 – IT
- VLAN 30 – Servers
- VLAN 40 – Guest Wi-Fi
- VLAN 99 – Network Management
- 802.1Q trunking
- Router-on-a-stick inter-VLAN routing
- DHCP for client devices
- WPA2-PSK wireless security with AES
- Separate Staff and Guest wireless networks
- ACL-based Guest Wi-Fi isolation

## Wireless Security

### Staff Wi-Fi
- SSID: PulaCloud-Staff
- Security: WPA2-PSK
- Encryption: AES

### Guest Wi-Fi
- SSID: PulaCloud-Guest
- Security: WPA2-PSK
- Encryption: AES

## Guest Isolation

Guest users are blocked from accessing:
- Staff network
- IT network
- Server network
- Management network

Testing evidence is included in the Phase 2 evidence files.
