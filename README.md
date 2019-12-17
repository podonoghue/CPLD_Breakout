# CPLD_Breakout
Break-out board for XC2C64A-7VQG44C CPLD

Features:  
* Alternative JTAG connectors (Xilinx 2x7 boxed header or simple 6-pin header)
* Simple header is right-angled so is keyed by proximity to the board 
* Reverse voltage protection by Schottky diode (assumes current limited supply!)
* Device programming pins are clamped to the __Gnd__/__Vdd__ to reduce damage from static or incorrect JTAG connector.
* Reset and debug LED
* Power indication LED
* Board pin spacing is suitable for bread-board (but __not__ DIL socket)
* 1.8V voltage regulator for CPLD
* Fixed 3.3V I/O

[Documentation](CPLD_Breakout.pdf)
