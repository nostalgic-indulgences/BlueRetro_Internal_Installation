# BlueRetro_Internal_Installation

Actual implementation videos can be found on the following YouTube channel:-
https://www.youtube.com/channel/UCARW91mtPx1urqnbG9ZfqSQ

**@ManCloud Current Trigger Component Listing**
</br>R1 - 4.7kΩ 0805 SMD Resistor
</br>R2 - 100kΩ 0805 SMD Resistor
</br>Q1 - YJS2301A SOT-23-6 DUAL P-Channel MOSFET (Lowest forward voltage drop I could find)
</br>Q2 - BSS123 / BSS138 / A2SHB SOT-23 N-Channel MOSFET

**@ManCloud Current Trigger Pinout**
</br>J1   - 3.3V/5.0V
</br>J1.1 - Controller 3.3V/5.0V
</br>J2   - 3.3V/5.0V Port Detection Sense Signal
</br>J2.1 - GND
</br>*** 5.0V Consoles only!!! 
</br>*** Bridge J2 & J2.1 with a 200kΩ 0805 SMD Resistor to create voltage divider to output 3.3V sense signal to ESP32
