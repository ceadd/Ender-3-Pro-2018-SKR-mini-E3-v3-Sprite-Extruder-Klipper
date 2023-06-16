This is very much a work in progress. Not tested, probably dont do it. 
This page will be updated when its working.

# Ender 3 Pro (2018)
BIGTREETECH SKR mini E3 v3.0
Creality Sprite Extruder Pro
Antclabs BL Touch (Genuine)
Raspberry Pi (Mainsail OS)

Made by CEADD - ceadd.ca
Special thanks to bigtreetech, jamesh1978 and nopp

To use this config, the firmware should be compiled for the
STM32G0B1 with a "8KiB bootloader" and USB communication.

The "make flash" command does not work on the SKR mini E3. Instead,
after running "make", copy the generated "out/klipper.bin" file to a
file named "firmware.bin" on an SD card and then restart the SKR
mini E3 with that SD card.
