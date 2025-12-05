# Preamp
Headphone amplifier with the following features:

- USBC Power Input
- 5V, 3.3V, 3.3VA, and 1.8V LDOs
- +/-12V split rail switching converter, feeding +/-10V and +/-5V LDOs
- ESP32 Module for control and driving a spectrum visualizer OLED display
- York Pico USB to I2S module
- ADAU1701 DSP
- PCM5102A Digital to Analog Converter
- PGA2311 digital volume controller

![block_diagram](https://github.com/user-attachments/assets/0ab7cf59-2694-4c74-ad1f-6dec4d1868a6)
<img width="822" height="552" alt="CAD" src="https://github.com/user-attachments/assets/4e9519e5-2cdd-4568-832d-b684f2f3d2b4" />


**To Do:**
[x] Update Block Diagram with power architecture changes

Layout:
[ ] Verify component placement
[ ] Routing!

Schematic:
[ ] Clean up placement<br/>
[ ] Part selection for capacitors, verify voltages on schematic
[x] Reduce footprint sizes where possible, mainly capacitors
[x] Pick proper connectors for the front panel stuff
[ ] Decide on header stack height for the York and ESP32

ESP32 Code
[ ] Port over spectrum visualizer
[ ] PGA control

CAD
[x] Import board step file
[x] Figure out rear mounting
[ ] Layout front/rear panels 
