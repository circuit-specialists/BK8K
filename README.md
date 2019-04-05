# BK8K

## EEPROM Dump Command
* avrdude -p m8 -P {COM} -c avrisp -b 19200 -U eeprom:r:eeprom_dump.txt

* Repo Contains
    - binary memory dump from MCU
    - binary dump converted to assembly instructions

### Rear Panel Screw sizes
    - 4x 8-32x3/4 nylon bolt
    - 4x 8-32 nylon hex nut
    - 4x #8 nylon washer