# BK8K

## EEPROM Dump Command
* avrdude -p m8 -P {COM} -c avrisp -b 19200 -U eeprom:r:eeprom_dump.txt

* Repo Contains
    - binary memory dump from MCU
    - binary dump converted to assembly instructions