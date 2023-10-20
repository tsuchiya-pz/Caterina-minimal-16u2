# Caterina-minimal-16u2
I modified caterina bootloader a little. 

Forked from: https://github.com/arduino/ArduinoCore-avr/tree/master/bootloaders/caterina

commit: https://github.com/arduino/ArduinoCore-avr/commit/1668039101ddee651f9b8e9b763134e0a5aebf59

this bootloader is for atmega16u2.

## to build this bootloader

1. download lufa-111009 from https://www.fourwalledcubicle.com/LUFA.php
2. MODIFY Makefile
   - WRITE your USB PID and VID.
   - MODIFY LUFA_PATH (line 128)
