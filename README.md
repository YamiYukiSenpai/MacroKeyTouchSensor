# MacroKeyTouchSensor

## Parts
* Raspberry Pi + microSD card
* Copper tape
* A platform
    *  Can be cardboard, acrylic casing (like mine)
*  Wire strippers
*  Breadboard cables

Note: expect to pay roughly $150 in parts

# Time Commitment
The hardware portion of the project can be done in about a week

## Connecting the MPR121 breakout sensor to the Raspberry Pi
* Connect the following pins on the MPR121 breakout board to the Raspberry Pi
    *  MPR121 Vin - Pi 3.3V
    *  MPR121 GND - Pi GND
    *  MPR121 SCL - Pi SCL
    *  MPR121 SDA - Pi SDA

* Make sure that the Pi can detect any I2C input
