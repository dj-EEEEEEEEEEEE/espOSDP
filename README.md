# espOSDP

espOSDP is a ESP32-based OSDP v2 access control panel designed to run on an ESP32 Wroom V3.
It supports OSDP Secure Channel, HID Signo readers, LED and beeper control, and a web-based
management interface.

## Features
- OSDP v2 Control Panel
- Secure Channel support
- HID Signo reader compatibility
- Reader LED and beeper control
- Web-based configuration and monitoring
- Modular hardware and software design
- Custom PCB IO Interface

## Architecture
- libosdp for protocol handling
- FastAPI backend
- Web frontend (TBD)
- Isolated RS-485 reader ports

## Status
Working and in development.
Currently bringing up libosdp CP with HID Signo readers.

## Disclaimer
This project is for educational and research purposes.
It is not certified for life-safety or regulated security deployments.
