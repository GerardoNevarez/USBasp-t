Status of this fork:
* Successfully flashed one ATTiny84 with another ATTiny84. (SPI) Hardware: (https://github.com/AndersBNielsen/v-usb-businesscard)
* ATTiny85 support might be broken
* TPI not updated or tested

Uses PA4(SCL), PA6(MOSI), PA5(MISO), PA7 (SS / reset)

# Note: This is a fork to support Attiny84 too. I will try to leave support for ATTiny85 intact. Original readme below. #

## micro - USBasp ##

This is a work in progress. 

* Port of USBasp to ATtiny 85
* Design of optimized hardware

Why?

* It's fun.
* USBasp is a de-facto standard for small USB-AVR programmers. It's the only one to support TPI.
* Porting it to ATtiny85 allows for a smaller and cheaper circuit. Cheaper MCU, no Xtal, etc...

This software is based on Thomas Fischl's USBasp. See readme.txt for original comments.

### Status ####

Software:

* USBasp sucessfully compiles for the ATTiny85.
* micronucleus works as a bootloader.
* USB device is recognized as USBasp and communicates with AVRdude.
* Software tested on microUSB hardware. Both TPI and SPI seem to work.

Hardware:

* Revision 0.5 sent to OSH park for pcb manufacturing.
* Update v1.1 done, ready for manufacturing.
* Update 02/08/2013: All parts received, first device built.

### Hardware ###

Circuit:  
![Circuit](/hardware/u-usbasp-circuit.png)

v1.1 PCB front side:  
![V1.1 PCB front](/hardware/microusbasp_frontside.jpg)

v1.1 PCB rear side:   
![V1.1 PCB rear](/hardware/microusbasp_rearside.jpg)

