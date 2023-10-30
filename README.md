# BlueRetro Internal Installation Guides

Actual implementation videos can be found on the following YouTube channel:-
https://www.youtube.com/channel/UCARW91mtPx1urqnbG9ZfqSQ

</u>Current Trigger for Port Detection

**@ManCloud Current Trigger Component Listing**
</br>R1 - 4.7kΩ 0805 SMD Resistor
</br>R2 - 100kΩ 0805 SMD Resistor
</br>Q1 - YJS2301A SOT-23-6 DUAL P-Channel MOSFET (Lowest forward voltage drop I could find)
</br>Q2 - BSS123 / BSS138 / A2SHB SOT-23 N-Channel MOSFET

**@ManCloud Current Trigger Pinout**
</br>J1.1 - Console 3.3V/5.0V
</br>J1.2 - Controller 3.3V/5.0V
</br>J2.1 - ESP32 3.3V Port Detection Sense Signal
</br>J2.2 - GND
</br>*** 5.0V Consoles only!!! 
</br>*** Bridge J2.1 & J2.2 with a 200kΩ 0805 SMD Resistor to create voltage divider to output 3.3V sense signal to ESP32
