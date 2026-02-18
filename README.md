# packet-sniffer
Python raw socket based packet sniffer

A simple packet sniffer built using Python raw sockets.

## Features
- Captures Ethernet Frames
- Extracts IPv4 Packets
- Detects:
  - ICMP
  - TCP
  - UDP
- Displays source/destination MAC and IP
- Shows TCP flags

## Technologies Used
- Python
- socket
- struct

## How to Run

⚠ Requires Linux (uses raw sockets)

```bash
sudo python3 sniffer.py
