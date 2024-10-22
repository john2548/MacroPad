# MacroPad

this github Repo holds all design info, code, and files pertaining to my Numberpad + key macro device im currently calling the MacroPad. 

[INSERT BASIC INFO HERE]
![image](https://github.com/user-attachments/assets/0c653a97-d454-48dd-b54b-8fcd71780e4e)

the device is a standard numpad with an extra column that controls user generated macros and shortcuts. device also has an added rotary encoder which serves as a media controller. there is an OLED screen on the device to show the current macro profile and potentially other system info.

this project uses the QMK firmware framework


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
  * W25Q128JVS 128 MBit (16MB) flash memory
- PCB:
  * RP2040 MCU
  * HRO-TYPE-C-31-M-12 USB-C connector
  * W25Q128JVS 128 MBit (16MB) flash memory
  * PRTR5VOU2X ESD protection
  * ABM8-272-T3 crystal oscillator
  * 22 SK6812MINI NeoPixel LEDs
  * RT9080-33GJ5 LDO Voltage Regulators 2 A IQ, 600mA Low-Dropout Linear
  * PEC11-4215F-S24 Rotary Encoder
  * 1.3" 128x64 SH1106G SPI OLED Monochrome Display
  * [INSERT LINE DRIVER HERE]
  * 22 [INSERT KEYBOARD SWITCHES HERE]
  * [INSERT LIST OF CAPACITORS AND RESISTORS HERE]

## NOTES:
- since flash memory utilizes QSPI instead of the main, both SPI slots are open to use
- SPI slot usage:
    * SPI0: SPI interface for bootloader
    * SPI1: OLED Display

## FUTURE IDEAS:
- develop housing for MacroPad
