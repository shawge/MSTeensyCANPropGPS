MSCan_Gauge
===========

This project uses a Teensy 3.1 microcontroller (https://www.pjrc.com/teensy/index.html) to interface with a Megasquirt 3 open source standalone
engine controller (http://www.msextra.com/) via CAN bus. Data is both received from the ECU and shown on a display and sent from attached devices back to the ECU.

## Hardware used
* The Teensy has an onboard CAN controller, however it needs a transceiver (Ebay, etc).
* [Adafruit 128x64 monochrome OLED display](http://www.adafruit.com/products/938) connected via SPI.
* [Adafruit 3 axis digital accelerometer](http://www.msextra.com/) connected via i2c.
* [Adafruit Ultimate GPS breakout](http://www.adafruit.com/products/746) connected via serial.
* [Adafruit 16 LED Neopixel ring](http://www.adafruit.com/products/1463)
* [Adafruit rotary encoder](http://www.adafruit.com/products/377)
