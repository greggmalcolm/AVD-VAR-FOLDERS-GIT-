
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 374 | 373 | 1 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| AVD-VEOS1 |  33 | 33 | 0 | - |
| AVD-VEOS2 |  33 | 33 | 0 | - |
| AVD-VEOS3 |  51 | 51 | 0 | - |
| AVD-VEOS4 |  51 | 51 | 0 | - |
| AVD-VEOS5 |  51 | 51 | 0 | - |
| AVD-VEOS6 |  51 | 51 | 0 | - |
| AVD-VEOS7 |  52 | 52 | 0 | - |
| AVD-VEOS8 |  52 | 51 | 1 | Interface State |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  8 | 8 | 0 |
| Interface State |  124 | 123 | 1 |
| LLDP Topology |  36 | 36 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  24 | 24 | 0 |
| BGP |  62 | 62 | 0 |
| Routing Table |  66 | 66 | 0 |
| Loopback0 Reachability |  48 | 48 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 64 | AVD-VEOS8 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch32_Switch32 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | AVD-VEOS1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | AVD-VEOS2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | AVD-VEOS3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | AVD-VEOS4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | AVD-VEOS5 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | AVD-VEOS6 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | AVD-VEOS7 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | AVD-VEOS8 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS3_Ethernet1 | PASS | - |
| 10 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS4_Ethernet1 | PASS | - |
| 11 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_AVD-VEOS5_Ethernet1 | PASS | - |
| 12 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_AVD-VEOS6_Ethernet1 | PASS | - |
| 13 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_AVD-VEOS7_Ethernet1 | PASS | - |
| 14 | AVD-VEOS1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_AVD-VEOS8_Ethernet1 | PASS | - |
| 15 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS3_Ethernet2 | PASS | - |
| 16 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS4_Ethernet2 | PASS | - |
| 17 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_AVD-VEOS5_Ethernet2 | PASS | - |
| 18 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_AVD-VEOS6_Ethernet2 | PASS | - |
| 19 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_AVD-VEOS7_Ethernet2 | PASS | - |
| 20 | AVD-VEOS2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_AVD-VEOS8_Ethernet2 | PASS | - |
| 21 | AVD-VEOS3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS4_Ethernet3 | PASS | - |
| 22 | AVD-VEOS3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS4_Ethernet4 | PASS | - |
| 23 | AVD-VEOS3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet1 | PASS | - |
| 24 | AVD-VEOS3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet1 | PASS | - |
| 25 | AVD-VEOS3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch30_Gi0/0 | PASS | - |
| 26 | AVD-VEOS4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS3_Ethernet3 | PASS | - |
| 27 | AVD-VEOS4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS3_Ethernet4 | PASS | - |
| 28 | AVD-VEOS4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet2 | PASS | - |
| 29 | AVD-VEOS4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet2 | PASS | - |
| 30 | AVD-VEOS4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch30_Gi0/1 | PASS | - |
| 31 | AVD-VEOS5 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS6_Ethernet3 | PASS | - |
| 32 | AVD-VEOS5 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS6_Ethernet4 | PASS | - |
| 33 | AVD-VEOS5 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet3 | PASS | - |
| 34 | AVD-VEOS5 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet3 | PASS | - |
| 35 | AVD-VEOS5 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch31_Gi0/0 | PASS | - |
| 36 | AVD-VEOS6 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS5_Ethernet3 | PASS | - |
| 37 | AVD-VEOS6 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS5_Ethernet4 | PASS | - |
| 38 | AVD-VEOS6 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet4 | PASS | - |
| 39 | AVD-VEOS6 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet4 | PASS | - |
| 40 | AVD-VEOS6 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch31_Gi0/1 | PASS | - |
| 41 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS8_Ethernet3 | PASS | - |
| 42 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS8_Ethernet4 | PASS | - |
| 43 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet5 | PASS | - |
| 44 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet5 | PASS | - |
| 45 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch32_Gi0/0 | PASS | - |
| 46 | AVD-VEOS7 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - Routed interface to IOL22 | PASS | - |
| 47 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AVD-VEOS7_Ethernet3 | PASS | - |
| 48 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AVD-VEOS7_Ethernet4 | PASS | - |
| 49 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AVD-VEOS1_Ethernet6 | PASS | - |
| 50 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AVD-VEOS2_Ethernet6 | PASS | - |
| 51 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - switch32_Gi0/1 | PASS | - |
| 52 | AVD-VEOS8 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - Routed interface to IOL22 | PASS | - |
| 53 | AVD-VEOS3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS4_Po3 | PASS | - |
| 54 | AVD-VEOS3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch30_Switch30 | PASS | - |
| 55 | AVD-VEOS4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS3_Po3 | PASS | - |
| 56 | AVD-VEOS4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch30_Switch30 | PASS | - |
| 57 | AVD-VEOS5 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS6_Po3 | PASS | - |
| 58 | AVD-VEOS5 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch31_Switch31 | PASS | - |
| 59 | AVD-VEOS6 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS5_Po3 | PASS | - |
| 60 | AVD-VEOS6 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch31_Switch31 | PASS | - |
| 61 | AVD-VEOS7 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS8_Po3 | PASS | - |
| 62 | AVD-VEOS7 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch32_Switch32 | PASS | - |
| 63 | AVD-VEOS8 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AVD-VEOS7_Po3 | PASS | - |
| 64 | AVD-VEOS8 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - switch32_Switch32 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 65 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 66 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 67 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 68 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 69 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 70 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 71 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 72 | AVD-VEOS3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 73 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 74 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 75 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 76 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 77 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 78 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 79 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 80 | AVD-VEOS4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 81 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 82 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 83 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 84 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 85 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 86 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 87 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 88 | AVD-VEOS5 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 89 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 90 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 91 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 92 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 93 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 94 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 95 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 96 | AVD-VEOS6 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 97 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 98 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 99 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 100 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 101 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 102 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 103 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 104 | AVD-VEOS7 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 105 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 106 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 107 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 108 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 109 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 110 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 111 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 112 | AVD-VEOS8 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 113 | AVD-VEOS3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 114 | AVD-VEOS4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 115 | AVD-VEOS5 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 116 | AVD-VEOS6 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 117 | AVD-VEOS7 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 118 | AVD-VEOS8 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 119 | AVD-VEOS1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 120 | AVD-VEOS2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 121 | AVD-VEOS3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 122 | AVD-VEOS3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 123 | AVD-VEOS4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 124 | AVD-VEOS4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 125 | AVD-VEOS5 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 126 | AVD-VEOS5 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 127 | AVD-VEOS6 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 128 | AVD-VEOS6 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 129 | AVD-VEOS7 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 130 | AVD-VEOS7 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 131 | AVD-VEOS8 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 132 | AVD-VEOS8 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 133 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS3_Ethernet1 | PASS | - |
| 134 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS4_Ethernet1 | PASS | - |
| 135 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS5_Ethernet1 | PASS | - |
| 136 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS6_Ethernet1 | PASS | - |
| 137 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: AVD-VEOS7_Ethernet1 | PASS | - |
| 138 | AVD-VEOS1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: AVD-VEOS8_Ethernet1 | PASS | - |
| 139 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS3_Ethernet2 | PASS | - |
| 140 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS4_Ethernet2 | PASS | - |
| 141 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS5_Ethernet2 | PASS | - |
| 142 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS6_Ethernet2 | PASS | - |
| 143 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: AVD-VEOS7_Ethernet2 | PASS | - |
| 144 | AVD-VEOS2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: AVD-VEOS8_Ethernet2 | PASS | - |
| 145 | AVD-VEOS3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS4_Ethernet3 | PASS | - |
| 146 | AVD-VEOS3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS4_Ethernet4 | PASS | - |
| 147 | AVD-VEOS3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet1 | PASS | - |
| 148 | AVD-VEOS3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet1 | PASS | - |
| 149 | AVD-VEOS4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS3_Ethernet3 | PASS | - |
| 150 | AVD-VEOS4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS3_Ethernet4 | PASS | - |
| 151 | AVD-VEOS4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet2 | PASS | - |
| 152 | AVD-VEOS4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet2 | PASS | - |
| 153 | AVD-VEOS5 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS6_Ethernet3 | PASS | - |
| 154 | AVD-VEOS5 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS6_Ethernet4 | PASS | - |
| 155 | AVD-VEOS5 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet3 | PASS | - |
| 156 | AVD-VEOS5 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet3 | PASS | - |
| 157 | AVD-VEOS6 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS5_Ethernet3 | PASS | - |
| 158 | AVD-VEOS6 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS5_Ethernet4 | PASS | - |
| 159 | AVD-VEOS6 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet4 | PASS | - |
| 160 | AVD-VEOS6 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet4 | PASS | - |
| 161 | AVD-VEOS7 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS8_Ethernet3 | PASS | - |
| 162 | AVD-VEOS7 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS8_Ethernet4 | PASS | - |
| 163 | AVD-VEOS7 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet5 | PASS | - |
| 164 | AVD-VEOS7 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet5 | PASS | - |
| 165 | AVD-VEOS8 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AVD-VEOS7_Ethernet3 | PASS | - |
| 166 | AVD-VEOS8 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AVD-VEOS7_Ethernet4 | PASS | - |
| 167 | AVD-VEOS8 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AVD-VEOS1_Ethernet6 | PASS | - |
| 168 | AVD-VEOS8 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AVD-VEOS2_Ethernet6 | PASS | - |
| 169 | AVD-VEOS3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 170 | AVD-VEOS4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 171 | AVD-VEOS5 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 172 | AVD-VEOS6 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 173 | AVD-VEOS7 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 174 | AVD-VEOS8 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 175 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet1 - Destination: AVD-VEOS3_Ethernet1 | PASS | - |
| 176 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet2 - Destination: AVD-VEOS4_Ethernet1 | PASS | - |
| 177 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet3 - Destination: AVD-VEOS5_Ethernet1 | PASS | - |
| 178 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet4 - Destination: AVD-VEOS6_Ethernet1 | PASS | - |
| 179 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet5 - Destination: AVD-VEOS7_Ethernet1 | PASS | - |
| 180 | AVD-VEOS1 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS1_Ethernet6 - Destination: AVD-VEOS8_Ethernet1 | PASS | - |
| 181 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet1 - Destination: AVD-VEOS3_Ethernet2 | PASS | - |
| 182 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet2 - Destination: AVD-VEOS4_Ethernet2 | PASS | - |
| 183 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet3 - Destination: AVD-VEOS5_Ethernet2 | PASS | - |
| 184 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet4 - Destination: AVD-VEOS6_Ethernet2 | PASS | - |
| 185 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet5 - Destination: AVD-VEOS7_Ethernet2 | PASS | - |
| 186 | AVD-VEOS2 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS2_Ethernet6 - Destination: AVD-VEOS8_Ethernet2 | PASS | - |
| 187 | AVD-VEOS3 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS3_Ethernet1 - Destination: AVD-VEOS1_Ethernet1 | PASS | - |
| 188 | AVD-VEOS3 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS3_Ethernet2 - Destination: AVD-VEOS2_Ethernet1 | PASS | - |
| 189 | AVD-VEOS4 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS4_Ethernet1 - Destination: AVD-VEOS1_Ethernet2 | PASS | - |
| 190 | AVD-VEOS4 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS4_Ethernet2 - Destination: AVD-VEOS2_Ethernet2 | PASS | - |
| 191 | AVD-VEOS5 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS5_Ethernet1 - Destination: AVD-VEOS1_Ethernet3 | PASS | - |
| 192 | AVD-VEOS5 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS5_Ethernet2 - Destination: AVD-VEOS2_Ethernet3 | PASS | - |
| 193 | AVD-VEOS6 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS6_Ethernet1 - Destination: AVD-VEOS1_Ethernet4 | PASS | - |
| 194 | AVD-VEOS6 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS6_Ethernet2 - Destination: AVD-VEOS2_Ethernet4 | PASS | - |
| 195 | AVD-VEOS7 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS7_Ethernet1 - Destination: AVD-VEOS1_Ethernet5 | PASS | - |
| 196 | AVD-VEOS7 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS7_Ethernet2 - Destination: AVD-VEOS2_Ethernet5 | PASS | - |
| 197 | AVD-VEOS8 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS8_Ethernet1 - Destination: AVD-VEOS1_Ethernet6 | PASS | - |
| 198 | AVD-VEOS8 | IP Reachability | ip reachability test p2p links | Source: AVD-VEOS8_Ethernet2 - Destination: AVD-VEOS2_Ethernet6 | PASS | - |
| 199 | AVD-VEOS1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 200 | AVD-VEOS2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 201 | AVD-VEOS3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 202 | AVD-VEOS4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 203 | AVD-VEOS5 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 204 | AVD-VEOS6 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 205 | AVD-VEOS7 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 206 | AVD-VEOS8 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 207 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.9 | PASS | - |
| 208 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.13 | PASS | - |
| 209 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.17 | PASS | - |
| 210 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.21 | PASS | - |
| 211 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.25 | PASS | - |
| 212 | AVD-VEOS1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.29 | PASS | - |
| 213 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.11 | PASS | - |
| 214 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.15 | PASS | - |
| 215 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.19 | PASS | - |
| 216 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.23 | PASS | - |
| 217 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.27 | PASS | - |
| 218 | AVD-VEOS2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.31 | PASS | - |
| 219 | AVD-VEOS3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 220 | AVD-VEOS3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.8 | PASS | - |
| 221 | AVD-VEOS3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.10 | PASS | - |
| 222 | AVD-VEOS4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 223 | AVD-VEOS4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.12 | PASS | - |
| 224 | AVD-VEOS4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.14 | PASS | - |
| 225 | AVD-VEOS5 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 226 | AVD-VEOS5 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.16 | PASS | - |
| 227 | AVD-VEOS5 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.18 | PASS | - |
| 228 | AVD-VEOS6 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 229 | AVD-VEOS6 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.20 | PASS | - |
| 230 | AVD-VEOS6 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.22 | PASS | - |
| 231 | AVD-VEOS7 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.13 | PASS | - |
| 232 | AVD-VEOS7 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.24 | PASS | - |
| 233 | AVD-VEOS7 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.26 | PASS | - |
| 234 | AVD-VEOS8 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.12 | PASS | - |
| 235 | AVD-VEOS8 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.28 | PASS | - |
| 236 | AVD-VEOS8 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.30 | PASS | - |
| 237 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.5 | PASS | - |
| 238 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.6 | PASS | - |
| 239 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.7 | PASS | - |
| 240 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.8 | PASS | - |
| 241 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.9 | PASS | - |
| 242 | AVD-VEOS1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.10 | PASS | - |
| 243 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.5 | PASS | - |
| 244 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.6 | PASS | - |
| 245 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.7 | PASS | - |
| 246 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.8 | PASS | - |
| 247 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.9 | PASS | - |
| 248 | AVD-VEOS2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.10 | PASS | - |
| 249 | AVD-VEOS3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 250 | AVD-VEOS3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 251 | AVD-VEOS4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 252 | AVD-VEOS4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 253 | AVD-VEOS5 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 254 | AVD-VEOS5 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 255 | AVD-VEOS6 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 256 | AVD-VEOS6 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 257 | AVD-VEOS7 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 258 | AVD-VEOS7 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 259 | AVD-VEOS8 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.1 | PASS | - |
| 260 | AVD-VEOS8 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.255.2 | PASS | - |
| 261 | AVD-VEOS3 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 262 | AVD-VEOS3 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 263 | AVD-VEOS3 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 264 | AVD-VEOS4 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 265 | AVD-VEOS4 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 266 | AVD-VEOS4 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 267 | AVD-VEOS5 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 268 | AVD-VEOS5 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 269 | AVD-VEOS5 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 270 | AVD-VEOS6 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 271 | AVD-VEOS6 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 272 | AVD-VEOS6 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 273 | AVD-VEOS7 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 274 | AVD-VEOS7 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 275 | AVD-VEOS7 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 276 | AVD-VEOS8 | Routing Table | Remote VTEP address | 192.168.254.5 | PASS | - |
| 277 | AVD-VEOS8 | Routing Table | Remote VTEP address | 192.168.254.7 | PASS | - |
| 278 | AVD-VEOS8 | Routing Table | Remote VTEP address | 192.168.254.9 | PASS | - |
| 279 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 280 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 281 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 282 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 283 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 284 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 285 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 286 | AVD-VEOS3 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 287 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 288 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 289 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 290 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 291 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 292 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 293 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 294 | AVD-VEOS4 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 295 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 296 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 297 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 298 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 299 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 300 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 301 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 302 | AVD-VEOS5 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 303 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 304 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 305 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 306 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 307 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 308 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 309 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 310 | AVD-VEOS6 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 311 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 312 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 313 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 314 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 315 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 316 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 317 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 318 | AVD-VEOS7 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 319 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.1 | PASS | - |
| 320 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.2 | PASS | - |
| 321 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.5 | PASS | - |
| 322 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.6 | PASS | - |
| 323 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.7 | PASS | - |
| 324 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.8 | PASS | - |
| 325 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.9 | PASS | - |
| 326 | AVD-VEOS8 | Routing Table | Remote Lo0 address | 192.168.255.10 | PASS | - |
| 327 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.1 | PASS | - |
| 328 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.2 | PASS | - |
| 329 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.5 | PASS | - |
| 330 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.6 | PASS | - |
| 331 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.7 | PASS | - |
| 332 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.8 | PASS | - |
| 333 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.9 | PASS | - |
| 334 | AVD-VEOS3 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS3 - 192.168.255.5 Destination: 192.168.255.10 | PASS | - |
| 335 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.1 | PASS | - |
| 336 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.2 | PASS | - |
| 337 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.5 | PASS | - |
| 338 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.6 | PASS | - |
| 339 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.7 | PASS | - |
| 340 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.8 | PASS | - |
| 341 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.9 | PASS | - |
| 342 | AVD-VEOS4 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS4 - 192.168.255.6 Destination: 192.168.255.10 | PASS | - |
| 343 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.1 | PASS | - |
| 344 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.2 | PASS | - |
| 345 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.5 | PASS | - |
| 346 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.6 | PASS | - |
| 347 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.7 | PASS | - |
| 348 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.8 | PASS | - |
| 349 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.9 | PASS | - |
| 350 | AVD-VEOS5 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS5 - 192.168.255.7 Destination: 192.168.255.10 | PASS | - |
| 351 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.1 | PASS | - |
| 352 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.2 | PASS | - |
| 353 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.5 | PASS | - |
| 354 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.6 | PASS | - |
| 355 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.7 | PASS | - |
| 356 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.8 | PASS | - |
| 357 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.9 | PASS | - |
| 358 | AVD-VEOS6 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS6 - 192.168.255.8 Destination: 192.168.255.10 | PASS | - |
| 359 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.1 | PASS | - |
| 360 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.2 | PASS | - |
| 361 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.5 | PASS | - |
| 362 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.6 | PASS | - |
| 363 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.7 | PASS | - |
| 364 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.8 | PASS | - |
| 365 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.9 | PASS | - |
| 366 | AVD-VEOS7 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS7 - 192.168.255.9 Destination: 192.168.255.10 | PASS | - |
| 367 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.1 | PASS | - |
| 368 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.2 | PASS | - |
| 369 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.5 | PASS | - |
| 370 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.6 | PASS | - |
| 371 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.7 | PASS | - |
| 372 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.8 | PASS | - |
| 373 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.9 | PASS | - |
| 374 | AVD-VEOS8 | Loopback0 Reachability | Loopback0 Reachability | Source: AVD-VEOS8 - 192.168.255.10 Destination: 192.168.255.10 | PASS | - |