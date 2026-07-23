## Shlomi Avidan

Computer and electronics engineer finishing an M.Sc. at Ben-Gurion University (autumn 2026). I work across three areas that rarely sit together: offensive security and reverse engineering, embedded hardware and firmware, and RF and mixed-signal circuit design.

- Reverse engineering, binary exploitation, and malware analysis (Ghidra, IDA, x64dbg)
- Bare-metal firmware on ARM microcontrollers, PCB design, and hardware bring-up
- RF circuit design, antennas, and microwave measurement
- 1st place, Iron Codes 2024 CTF (Tel Aviv University CyberWeek). Top 1000 worldwide (as of July 2026) on HackTheBox.

[LinkedIn](https://www.linkedin.com/in/shlomi-k-avidan/)

### Selected work

**[D-Link DSL-224 hardware security research](https://github.com/shlomika1337/dsl-224-research)** — *in progress*
Firmware extraction and vulnerability research on a Realtek RTL8685 DSL router. UART root shell, bit-exact 8 MB SPI flash dump (md5-verified end to end), SquashFS rootfs carving, and static analysis of the MIPS web stack in Ghidra. Hardware-level access built from a bare ESP8266.

**[Blind HID Injector — ADB enablement on a dead-display Android](https://github.com/shlomika1337/Pixel-6_Recovery_HID_Injector)**
A Raspberry Pi Pico (CircuitPython) presenting as a composite USB HID device that blindly drives the Android UI to enable USB Debugging on a Pixel 6 with a dead screen. Relative-to-absolute pointer calibration by corner-slamming, keyboard-driven focus traversal, and an honest write-up of where the technique hits its observability limit.

**[Check Point Security Academy 2020 CTF writeup](https://github.com/shlomika1337/ctf-writeups)**
Reverse engineered a custom network protocol from packet captures, recovered the XOR key of a challenge-response scheme, and built a working exploit past a CRC-32 integrity check. Also covers MITM via ARP spoofing with RC4 key recovery, plus cryptography, forensics, and steganography.

**[Arduino Nano SDI-12 to USB Bridge](https://github.com/shlomika1337/Arduino-Nano-SDI-12-to-USB-Bridge-for-HydraProbe)**
An embedded interface between an Arduino Nano and a Stevens HydraProbe soil sensor over the SDI-12 protocol, with a clean parser and full documentation.

**[CEE-Masters](https://github.com/shlomika1337/CEE-Masters)**
Graduate technical work in semiconductor devices and nanophotonics, including an independent reproduction and critique of a *Science* paper on dielectric metasurfaces (with my own MATLAB simulations), and first-principles reviews of solar-cell physics.

**[Donation Data Automation Pipeline](https://github.com/shlomika1337/bgu-remittance-automator)**
A multi-stage Python pipeline written by hand in 2022 that replaced a full-time manual data-processing role at BGU: cleaning and validating messy monthly financial spreadsheets, resolving donor IDs, and driving records into a Salesforce CRM.

**[Ultimate Lifeform — Garry's Mod SWEP](https://github.com/shlomika1337/ultimate-lifeform_gmod-addon)**
A ~1,000-line Lua weapon mod shipped on the Steam Workshop (~8,900 subscribers, 15,900 unique visitors). Client/server networking, the physics and entity API, engine-hook overrides with proper teardown, and world-to-screen HUD projection — self-taught against a sparsely-documented game engine, and maintained live across 31 updates.
