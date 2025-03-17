grbl4atmega32u4
===============

A GRBL hex file for ATmega32u4

### ABOUT ###

This a HEX file compiled from the source **grbl-atmega32u4-support-8c** *here*[https://github.com/rdpowers/grbl/tree/atmega32u4-support-8c] with WINAVR.
### NOTICE ###

It will be used on my **Arduino Leonardo** for a DIY laser engraver without fully test.

---------------
#### update ####
2014-04-11
There is a **LUFA CDC DEMO dirver** problem on WINDOWS XP. It's seems that [Windows Driver Installer](http://www.pjrc.com/teensy/usb_serial.html) may function as driver for LUFA.

2014-04-12
After install [Windows Driver Installer](http://www.pjrc.com/teensy/usb_serial.html),A **Teensy USB serial** will list on the *Ports (com and lpt1)* for *Device manager* .Then **grbl-atmega32u4-support-8c** works well as gcode interpreter for Arduino Leonardo on Windows XP. 
