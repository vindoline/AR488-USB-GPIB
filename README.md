# AR488-USB-GPIB
PCB for AR488 USB-GPIB adapter project.

This board maps out the physical pin mapping required by the AR488 sketch and emluates an Arduino UNO board. The USB interface is implemented with an FTDI FT232RL chip for maximum compatibility. The board requires an ATMEGA328P chip with an Arduino bootloader installed. Placing SW1 in the 'prog' position allows the Arduino IDE to automatically 'reset' the chip for easy upload of sketches. SW1 must be placed in the 'Run' position when using the USB-GPIB adapter.

The Gerbers have been uploaded and shared at OSHPark: https://oshpark.com/shared_projects/zpvaL7rz

The AR488 USB-GPIB adapter project is hosted at:https://github.com/Twilight-Logic/AR488
Comments and feedback can be provided here: https://www.eevblog.com/forum/projects/ar488-arduino-based-gpib-adapter/
Based on original work by Emanuele Girlando: http://egirland.blogspot.com/2014/03/arduino-uno-as-usb-to-gpib-controller.html
