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
<img width="859" height="575" alt="Capture" src="https://github.com/user-attachments/assets/7675650f-9f69-47a5-aeb8-d7bf339ea708" />



**To Do:** <br/>
[x] Update Block Diagram with power architecture changes<br/>

Layout:<br/>
[x] Verify component placement<br/>
[x] Routing!<br/>

Schematic:<br/>
[x] Clean up placement<br/>
[x] Part selection for capacitors, verify voltages on schematic<br/>
[x] Reduce footprint sizes where possible, mainly capacitors<br/>
[x] Pick proper connectors for the front panel stuff<br/>
[ ] Decide on header stack height for the York and ESP32<br/>

ESP32 Code<br/>
[x] Port over spectrum visualizer<br/>
[ ] PGA control<br/>

CAD<br/>
[x] Import board step file<br/>
[x] Figure out rear mounting<br/>
[ ] Layout front/rear panels <br/>
