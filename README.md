# MSTeensyCANPropGPS
This project uses a Teensy 3.2 microcontroller to exchange data with a MegaSquirt MS3Pro engine controller over a CAN bus.

## Hardware used
* [Teensy 3.2 microcontroller](https://www.pjrc.com/store/teensy32.html)
* [Teensy Prop Shield](https://www.pjrc.com/store/prop_shield.html) connected via SPI and I2C.
  * 6-axis sensor, linear accelerometer and magnetometer
  * 3-axis angular rate gyroscope
  * Pressure/altitude and temperature
  * 2 watt audio amp
  * High speed 5V buffers for driving LEDs
  * 8MB flash
* [Adafruit Ultimate GPS](http://www.adafruit.com/products/746) connected via serial
  * Version 3, 66 channel w/ 10Hz updates
* [Waveshare CAN Transceiver](https://www.waveshare.com/sn65hvd230-can-board.htm) connected via serial
* [Color 320x240 TFT Touchscreen](https://www.pjrc.com/store/display_ili9341_touch.html) connected via SPI

Inspiration for this project is from 
* openhoon/MSCan_Gauge
* merkur2k/MSCan_Gauge
