# pico-solar-tracker
This is in development and these instructions are not complete. Additionally, most of the code is not commented. 
## About
This is an unofficial open source tool built for the Raspberry Pi Pico (2)W to poll and display local energy data. It is designed to be compatible with Fronius solar inverters that use the Fronius Solar API v1. While functional, bugs might be present. 
It fetches real time generation and system metrics directly from your local network without relying on any external services or servers, and displays it on an I2C screen. 
## Requirements
* Raspberry Pi Pico (2)W
* 3v3 or 5v I2C screen
* Jumper wires
* A breadboard or expansion board  

## Configuration Options
### Required
#### main.py
---
`fronius_ip:`: The location of where the inverter can be accessed. Ensure that this is connectable from the Pico's perspective. 

#### creds.py 
---
`ssid:`Your **2.4GHz** Wi-Fi SSID
`password:` Your SSID's password
### Optional
---

## Disclaimer
**Fronius and Solar.web are trademarks of Fronius International GmbH. This product is an independent open source tool. I am not affiliated with, sponsored by, or employed by Fronius International GmbH. 
Additionally, "Raspberry Pi" and "Raspberry Pi Pico" are trademarks of Raspberry Pi Ltd. I am also not affiliated with, sponsored by, or employed by Raspberry Pi Ltd.**