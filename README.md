# Electronics Merit Badge Kit (Legacy Version)
==================================

> ⚠️ **WARNING:** This version of the Resica Falls Scout Reservation Electronics Merit Badge Kit has **not been produced in several years**.  
> All information in this repository should be considered **deprecated**.  
> For the most recent version of the kit and up-to-date documentation, please visit the new repository:  
> 👉 [https://github.com/colbsa/Electronics-Merit-Badge-Kit](https://github.com/colbsa/Electronics-Merit-Badge-Kit) ← *(replace this link)*

![Electronics MB Kit Assembled](/Images/ElectronicsMBKit_Assembled.jpg?raw=true "Electronics MB Kit Assembled")

Small ATtiny (Arduino IDE Compatible) microcontroller based kit used to teach Electronics Merit Badge at Resica Falls Scout Reservation.  
Once assembled and functional, the kit allows selection of various LED display modes (Flickering Candle, Nightlight, Flashlight, Etc.)  
by rotating the on-board potentiometer. Kit design is intended to meet all relevant badge requirements and expose scouts to a variety of  
component types at the lowest cost possible.

---

## Repository Contents

* **/Hardware** - Eagle Schematic / PCB Layouts & Bill Of Materials  
    - PCB silkscreen periodically updated to match summer camp staff members currently teaching Electronics Merit Badge at Resica Falls Scout Reservation.  
    - Bill Of Materials includes vendors / part numbers from the last production run.  
* **/Software** - Demo Arduino sketch for the kit. Code is intended to be easy to understand for beginners.  
* **/Images** - Images of the kit, both assembled and in parts.

---

## Firmware Programming

As of the 2017 summer camp season, kit firmware is programmed using the following tools:

### Hardware  
An [Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3) and an [AVR Programmer Shield](http://www.electrodragon.com/w/AVR_Programmer_Arduino_Shield) with ZIF socket.

Image of programming rig: [/Images/ElectronicsMBProgrammingRig.jpg](https://raw.githubusercontent.com/crossfireprod/RFSR---Electronics-Merit-Badge-Kit/master/Images/ElectronicsMBProgrammingRig.jpg)

### Software  
The Arduino Uno is used as an in-system programmer (ISP) through use of the [ArduinoISP](https://github.com/arduino/ArduinoISP) sketch packaged with [Arduino 1.8.3](https://www.arduino.cc/en/main/software) to program the ATtiny 45/85 targets.  
ATtiny core files available from [David Mellis' GitHub Repository](https://github.com/damellis/attiny), using [full instructions published by High-Low Tech](http://highlowtech.org/?p=1695) allow the ATtiny AVR microcontrollers used in the kits to be programmed directly from the Arduino IDE.

---

## License

All contents of this repository are released under [Creative Commons Share-alike 4.0](http://creativecommons.org/licenses/by-sa/4.0/).  

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

Kit Design By: [*ZachCross.com*](https://ZachCross.com)
