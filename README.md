# Wanhao3dPrinter
Code for wanhao 5s 3d printer with modifications (heater bed controlled from motherboard)
This is 95% taken from 
https://github.com/Jacotheron/Repetier-1.0.3-Wanhao-D5S

I modified to support a thermistor (I'm using an E3V6 hotend) and the motherboard controlling a heated bed
Also added BLTouch support (need to test as I don't currently have a carriage that can hold it)

TODO
Update the thermocouple decouple code
Update the bed so when plugged in it sets the bed enabled flag in configuration file.
