<div align="center">

  <h1>ESP32-DIV — Kilaz Edition</h1>

  <p>Enhanced Wireless Security Research Toolkit — 87 Features</p>

<a href="https://ICBizLabs.github.io/ESP32-DIV-KILAZ/" title="Web Installer"><img src="https://img.shields.io/badge/Web_Installer-Launch-blue?style=for-the-badge&logo=google-chrome" alt="Web Installer"></a>

</div>

<br />

## Web Installer

Flash the firmware directly from your browser — no Arduino IDE required.

**[Launch Web Installer](https://ICBizLabs.github.io/ESP32-DIV-KILAZ/)**

- Requires **Chrome** or **Edge** (desktop) with Web Serial support
- For **V2 boards (ESP32-S3)** only — V1 boards must use Arduino IDE
- Includes serial monitor for real-time device output

### What's included

- **Kilaz V2** — Latest firmware for ESP32-S3 boards with TFT display, CC1101, and NRF24
- **V1.5** — Original ESP32-S3 firmware
- **SD Card Files** — Download the optional SD card content pack

<div>&nbsp;</div>

## Complete Feature List

### WiFi Tools (19 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | Packet Monitor | Real-time waterfall visualization of WiFi activity across all 14 channels |
| 2 | Beacon Spammer | Broadcast multiple fake SSIDs to flood WiFi scanners |
| 3 | WiFi Deauther | Send deauthentication frames to disconnect clients from access points |
| 4 | Deauth Detector | Passive monitor that alerts when deauthentication attacks are detected |
| 5 | WiFi Scanner | Network scanner with SSID, BSSID, RSSI signal bars, channel, encryption, and vendor name from OUI lookup |
| 6 | Captive Portal | Fake access point with login page for security awareness testing |
| 7 | Evil Twin Detect | Scans for duplicate SSIDs with different BSSIDs indicating evil twin attacks |
| 8 | Probe Sniffer | Captures probe requests to reveal what networks nearby devices are searching for |
| 9 | Hidden AP Detect | Discovers cloaked wireless networks through probe response analysis |
| 10 | Rogue AP Scanner | Compares detected APs against a whitelist to identify unauthorized access points |
| 11 | Channel Analyzer | Bar graph visualization of AP distribution across channels 1-14 |
| 12 | EAPOL Capture | Captures WPA/WPA2 4-way handshakes and saves as PCAP files |
| 13 | PMKID Capture | Captures PMKID from the first EAPOL message without requiring a full handshake |
| 14 | Karma Attack | Responds to all probe requests by creating APs matching any SSID devices search for |
| 15 | WiFi Geiger | Signal strength meter with real-time RSSI graph for tracking specific access points |
| 16 | Pwnagotchi Detect | Detect Pwnagotchi devices by monitoring for characteristic beacon frame patterns |
| 17 | Probe Flood | Flood network with probe requests for wireless stress testing |
| 18 | Ping Scanner | Scan local network for active hosts via ICMP ping sweep |
| 19 | Station Tracker | Track WiFi client devices and monitor their AP associations over time |

### Bluetooth Tools (16 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | BLE Jammer | Floods BLE advertising channels (37, 38, 39) to disrupt Bluetooth Low Energy connections |
| 2 | BLE Spoofer | Broadcasts fake BLE advertisements mimicking various devices |
| 3 | Sour Apple | Spoof Apple BLE proximity pairing packets to trigger popups on iOS devices |
| 4 | Sniffer | Passive BLE advertisement monitor showing device names, MAC addresses, RSSI |
| 5 | BLE Scanner | Active scanner with vendor name from OUI, company name, signal bars, distance estimation, TX power, and service UUIDs |
| 6 | Skimmer Detect | Detects 40+ Bluetooth skimmer module patterns (HC-05/06, BT04/05, JDY, HM, MLT series) with threat scoring |
| 7 | Camera Finder | Detects 50+ camera BLE patterns including Wyze, Ring, Blink, Arlo, Nest, Hikvision, and spy camera signatures |
| 8 | GATT Explorer | Connects to BLE devices and enumerates all services, characteristics, and descriptors |
| 9 | Android Spam | Broadcasts Samsung Galaxy Buds and Google FastPair packets to trigger pairing popups |
| 10 | Beacon Cloner | Scans for iBeacons, captures UUID/Major/Minor values, and rebroadcasts them |
| 11 | BLE Fuzzer | Sends malformed and randomized BLE packets to test device robustness |
| 12 | Flipper Detect | Detect Flipper Zero devices nearby by BLE advertisement patterns |
| 13 | Flipper Spam | Mimic Flipper Zero BLE advertisements |
| 14 | AirTag Spoof | Spoof Apple AirTag BLE signals for tracking awareness testing |
| 15 | Flock Detect | Detect persistent BLE trackers following you by monitoring for persistent nearby beacons |
| 16 | BLE Rubber Ducky | HID-over-GATT keyboard injection with DuckyScript-compatible scripts |

### 2.4GHz Tools (8 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | Scanner | NRF24-based spectrum analyzer scanning all 128 channels (2400-2527 MHz) |
| 2 | 2.4GHz Analyzer | Enhanced spectrum view with waterfall display showing signal history over time |
| 3 | Tracker Detector | Detects 12 tracker types: AirTag, Tile, SmartTag, Chipolo, Google Find My, Pebblebee, Moto Tag, Amazon Sidewalk, Eufy, Nut |
| 4 | Proto Kill | Disrupts various 2.4GHz protocols by flooding specific channels |
| 5 | Drone Detector | Identifies drone control signals and FPV video feeds (DJI, FrSky, etc.) |
| 6 | MouseJack Detect | Scans for vulnerable wireless keyboards and mice using unencrypted protocols |
| 7 | WiFi Cam Detect | Detects hidden WiFi cameras by analyzing traffic patterns |
| 8 | Multi-Channel 24 | Uses all 3 NRF24 modules simultaneously with presets for BLE, WiFi, Drone, Zigbee |

### IR Remote (9 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | IR Record | Record infrared signals from any remote control and save to SD card |
| 2 | Saved Profile | Browse and replay previously recorded IR signals from SD card |
| 3 | TV-B-Gone | Cycle through power-off codes for hundreds of TV brands |
| 4 | HVAC Controller | Pre-loaded IR codes for 12 AC brands (Samsung, LG, Daikin, Mitsubishi, Haier, Gree, Midea, Carrier, Panasonic, Toshiba, Fujitsu, Generic) |
| 5 | IR Brute Force | Iterate through IR code ranges to find working codes for unknown devices |
| 6 | Universal Remote | General-purpose IR remote with common button layouts for TV, audio, and appliance control |
| 7 | Protocol Analyzer | Decode and display IR protocol details (NEC, Samsung, Sony, RC5/6, etc.) with timing analysis |
| 8 | Macro Sequencer | Chain multiple IR commands into automated sequences with configurable delays |
| 9 | Flipper Import | Import and transmit Flipper Zero `.ir` files from SD card |

### SubGHz Tools (25 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | Replay Attack | Capture and replay SubGHz signals for fixed-code devices |
| 2 | SubGHz Jammer | Broadband jamming across 315/433/868/915 MHz |
| 3 | Saved Profile | Browse, manage, and replay previously captured signals from SD card |
| 4 | Freq Analyzer | Real-time spectrum analyzer for SubGHz bands |
| 5 | TPMS Decoder | Decodes tire pressure monitoring system signals (315/433 MHz) |
| 6 | Weather Decoder | Decodes Acurite, LaCrosse, Oregon Scientific, Fine Offset protocols. Temperature, humidity, wind, rainfall |
| 7 | Smart Meter | Decodes AMR meter transmissions (SCM, SCM+, IDM, R900, NETIDM) for electric, gas, and water meters |
| 8 | Relay Detector | Detects car key fob relay attack equipment |
| 9 | Bug Sweeper | Scans SubGHz spectrum for hidden RF transmitters and surveillance bugs |
| 10 | Bruteforce | Iterates through code ranges for simple fixed-code systems |
| 11 | ProtoView | Advanced protocol analyzer with timing analysis |
| 12 | Rolling Flaws | Tests for known vulnerabilities in rolling code implementations (KeeLoq, etc.) |
| 13 | Tesla Charge Port | Transmits the 315MHz signal that opens Tesla charge port doors |
| 14 | POCSAG Decoder | Real-time POCSAG pager decoder using CC1101 hardware 2-FSK demodulation. BCH error correction, multi-baud (512/1200/2400), numeric and alphanumeric decoding |
| 15 | Genie Recorder | Specialized recorder for Genie Intellicode garage door openers |
| 16 | RAW Recorder | Records any SubGHz signal with precise timing data for later analysis or replay |
| 17 | Freq Scanner | Automated scanner that sweeps through SubGHz bands looking for active transmissions |
| 18 | Garage Protocols | Pre-loaded codes for Linear, Chamberlain, LiftMaster, Genie, Craftsman |
| 19 | Car Key Analyzer | Multi-frequency capture with vehicle ID (20+ manufacturers), button detection, virtual remote save/replay |
| 20 | Doorbell Trigger | Frequency presets for common wireless doorbells with learn mode |
| 21 | Doorbell Brute | Optimized brute force with 12+ manufacturer prefixes (Byron, Friedland, Heath Zenith, etc.) |
| 22 | FZ Analyzer | Flipper Zero compatible frequency analyzer |
| 23 | Security Sensors | Decode wireless security sensor transmissions (door/window, motion, glass break) |
| 24 | Multi-Freq Scanner | Rapid frequency hopping across multiple SubGHz bands with simultaneous signal monitoring |
| 25 | Flipper File | Import and replay Flipper Zero `.sub` signal files from SD card |

### Tools & Settings (10 features)
| # | Feature | Description |
|---|---------|-------------|
| 1 | Serial Monitor | Built-in serial terminal for debug output |
| 2 | Update Firmware | OTA firmware updates via WiFi or SD card |
| 3 | Button Checker | Hardware diagnostic for all buttons |
| 4 | Brightness | Adjustable display brightness (saved to EEPROM) |
| 5 | Screen Timeout | Auto screen-off timer for battery preservation |
| 6 | LED Control | Status LED on/off |
| 7 | SubGHz Region | Select regional frequency plan (US/EU/JP) |
| 8 | Device Info | Firmware version, chip info, free RAM, CPU temp, battery voltage |
| 9 | WiFi Setup | On-screen keyboard for WiFi configuration |
| 10 | License | View license status and device information |

<div>&nbsp;</div>

## Hardware

Supports **ESP32-S3 V2 boards** with ILI9341 2.4" TFT display, PCF8574 I/O expander, 3x NRF24 modules, CC1101 SubGHz radio, and SD card slot.

<div>&nbsp;</div>

## Credits

- Original project by [CiferTech](https://github.com/cifertech/ESP32-DIV)
- SPI bus architecture fix by [JesseCHale](https://github.com/JesseCHale/ESP32-DIV)
- Kilaz enhancements by ICBizLabs

<div>&nbsp;</div>

## Disclaimer

This tool is provided for authorized security testing and educational purposes only. Users are responsible for ensuring they have proper authorization before using any features on networks or devices. Unauthorized access to computer systems is illegal.
