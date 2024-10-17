# MacroPad

this github Repo holds all design info, code, and files pertaining to my Numberpad + key macro device im currently calling the MacroPad. 

[INSERT BASIC INFO HERE]
![image](https://github.com/user-attachments/assets/0c653a97-d454-48dd-b54b-8fcd71780e4e)



## PARTS LIST

## TODO:
- create breadboard prototype

## NOTES:
- since flash memory utilizes QSPI instead of the main, both SPI slots are open to use
- SPI slot usage:
    * SPI0: SPI interface for bootloader
    * SPI1: OLED Display

## SECONDARY IDEAS:
- include rgb to indicate if numlock is on or off, which basic profile is active, and which keys have macros available (if a key has a macro, it will be lit)
