This is a project to give you a solid base to the Raspbery Pi and official touch screen to be used for a multitude of things. It is designed to be 3D printed, and requires a little soldering for assembly. 

Hardware List:

- Raspberry Pi 3 B+
- SD Card 
- Power adapter for Raspberry Pi
- Official Raspberry Pi 7" Touch Screen
- Ribbon cable
- 8 M2.5 x 4mm Screws
- 4 M3 x 6mm Screws
- 1 M5 x 60mm Bolt 
- 1 Locking M5 Nut
- 4 Jumper wires for connecting to GPIO
- 4cm small heat shrink tubing

Instructions:

*** These instructions require at least the USB A port on the Pi touchscreen be removed, possibly the micro usb port ***

- Print the model using supports, the heavier the base the better 
- Prep 4 jumper wires, leave the gpio pins on half the jumper, strip and tin one end of each
- De-solder both usb ports from the touchscreen PCB, alternatively, check if the micro usb port must be removed
- Solder the 4 jumpter wires to the 5V, GND, SCL and SDA pins on the screen
- Cover the open connections with heat shrink
- Remount the PCB onto the back of the screen using the 4 M2.5 x 4mm screws
- Connect the ribbon cable to the screen and Pi
- Drop the Pi into place, and screw it down with the remaining 4 M2.5 x 4mm screws (screws are currenlty too loose)
- Connect the pins to the Pi: 5V to 5V, GND to GND, SDA to GPIO pin 2, and SCL to GPIO pin 3
- 

To Do:

- Fix standoffs in model

- Write Instructions
- Possible Mini Sound Bar ?
- Audio Circuit
