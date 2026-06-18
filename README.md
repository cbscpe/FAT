# FAT

This is a collection of functions which allows access to a FAT16/FAT32 formatted SD-Card. Theses functions were developped 
during the development of my RLV12 Emulator. They are written entirely in AVRASM2 assembler. 

## Requirements

The functions are making use of some other modules I have written and requires a set of structures defined. To make definitions of structures in AVR assembler easier I have written a set of macroes.


- malloc()
- free()
- SD_CARD_Read
- print
