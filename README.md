# linux-shell-packet-capture
Mini Linux Shell with Real-Time Packet Capture in C
# Mini Linux Shell with Real-Time Packet Capture

## Description
This project implements a mini Linux shell with a real-time network packet sniffer using C and libpcap. Users can execute basic Linux commands and capture network packets live.

## Features
- Mini shell interface (`$` prompt)
- Execute commands: `ls`, `pwd`, `mkdir`, `cp`
- Capture live network packets
- Display: Packet number, Length, Source IP, Destination IP, Protocol
- Continuous capture until Ctrl+C

## How to Compile
```bash
gcc network_packet_sniffer.c -lpcap -o network_sniffer
