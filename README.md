# BlueRetro_Internal_Installation

Actual implementation videos can be found on the following YouTube channel:-
https://www.youtube.com/channel/UCARW91mtPx1urqnbG9ZfqSQ

@ManCloud Current Trigger Component Listing
R1 - 4.7kΩ 0805 SMD Resistor
R2 - 100kΩ 0805 SMD Resistor
Q1 - YJS2301A DUAL P-Channel MOSFET (Lowest forward voltage drop I could find)
Q2 - BSS123 / BSS138 / A2SHB N-Channel MOSFET

@ManCloud Current Trigger Pinout
J1   - 3.3V/5.0V
J1.1 - Controller 3.3V/5.0V
J2   - 3.3V/5.0V Port Detection Sense Signal
J2.1 - GND
*** 5.0V Consoles only!!! 
*** Bridge J2 & J2.1 with a 200kΩ 0805 SMD Resistor to create voltage divider to output 3.3V sense signal to ESP32
