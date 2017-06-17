# HC-SR04-Sensor-properly-working
Raspberry Pi 3, Python

Going through the internet I saw lots of people having the same problems with the HC-SR04 as I did.
There were no solutions for this problems:
-it returned values up to 4000cm
-the script got stuck when the sensor didn't recieve an  echo (Arduino users reported that they just recieved 0cm)

After trying a lot of methods, I figured out that these issues were quite simple to fix.


Things you need:
- HC-SR04
- RPi3 + Raspbian
- 330 Ohm Resistor
- 470 Ohm Resistor
- 10 kOhm Resistor
- 2N2222 NPN Transistor
- Jumper wires
