This project is for the NES / Famicom to be able to use flash chips for translations or replace dead roms. 

The multi adapter board is a prototype but should work. I will update once tested. MMC5 only board is confirmed working. Everything created in eagle. Feel free to use with credit.

Piggyback version included. You need to pull chip enable and connect to 5v to disable the rom.

MMC5 / PRG / CHR to 48TSOP Flash Adatper

Replace roms with this board. Use 5v 8megabit flash

Below are instructions for the multi-board adapter. You can use this even for 28 pin rom boards.

Place on back of rom. Pull rom CE/OE + pull high 

Bridge Pin1 and 3 for all EXCEPT 128kb chr or Nrom boards

MMC5: Bridge all six circled jumpers

CHR: Bridge 3rd Circle + 1st square for 256kb

PRG: Bridge 1st Circle + 2nd square for 512kb or Top pads for 256kb


Also included is a ram adapter for romhacks like megaman minus inifinity. use ram IS61C256AL


Oshpark links: 
Piggyback ver. https://oshpark.com/shared_projects/Uz4v9Vq7
Ram adapter https://oshpark.com/shared_projects/bVWn1u0x
MMC5 only ver. https://oshpark.com/shared_projects/fcmApdiZ

Special thanks to https://github.com/techav-homebrew/LCC32-DIP32-Flash-Adapter for saving me some time on the 32pin board. Everything else is custom, hence the included libraries. 
