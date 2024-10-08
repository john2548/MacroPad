# MacroPad

this github Repo holds all design info, code, and files pertaining to my Numberpad + key macro device im currently calling the MacroPad. 

[INSERT BASIC INFO HERE]
![image](https://github.com/user-attachments/assets/0c6bec20-e2c5-40c6-8d23-2378505fe5e3)


## PARTS LIST

## TODO:
- SPI header (circuit diagram)
- flash memory (circuit diagram)
- media controller / volume control (circuit diagram)
- LCD screen (circuit diagram)
- create breadboard prototype

## NOTES:
- since flash memory utilizes QSPI instead of the main, both SPI slots are open to use
- SPI slot usage:
    * SPI0: SPI interface for bootloader

## SECONDARY IDEAS:
- include rgb to indicate if numlock is on or off, which basic profile is active, and which keys have macros available (if a key has a macro, it will be lit)
