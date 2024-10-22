# MacroPad

this github Repo holds all design info, code, and files pertaining to my Numberpad + key macro device im currently calling the MacroPad. 

[INSERT BASIC INFO HERE]
![image](https://github.com/user-attachments/assets/0c653a97-d454-48dd-b54b-8fcd71780e4e)

the device is a standard numpad with an extra column that controls user generated macros and shortcuts. device also has an added rotary encoder which serves as a media controller. there is an OLED screen on the device to show the current macro profile and potentially other system info.


## TODO:
- create breadboard prototype
- write code for the microcontroller
- test design with breadboard prototype
- finish PCB design and routing
- order all parts necessary for the PCB
- assemble PCB
- test PCB

## PARTS LIST
- Prototype:
  * RaspberryPi Pico
- PCB:
  * RP2040 MCU

## NOTES:
- since flash memory utilizes QSPI instead of the main, both SPI slots are open to use
- SPI slot usage:
    * SPI0: SPI interface for bootloader
    * SPI1: OLED Display

## FUTURE IDEAS:
- develop housing for MacroPad
