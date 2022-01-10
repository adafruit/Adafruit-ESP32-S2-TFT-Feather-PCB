## Adafruit ESP32-S2 TFT Feather - 4MB Flash, 2MB PSRAM, STEMMA QT PCB

<a href="http://www.adafruit.com/products/5300"><img src="assets/5300.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ESP32-S2 TFT Feather - 4MB Flash, 2MB PSRAM, STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5300

### Description

We've got a new machine here at Adafruit, it can uncover your deepest desires. Don't believe me? I'll turn it on right now to prove it to you! What, you want unlimited mozzarella sticks? OK well, that's not something we can provide. But we can provide your second-deepest desire: an ESP32-S2 Feather board with a built in IPS TFT color display. It's got all the gooeyness of a mozzarella stick features of a Feather main board, the comforting warmth of an ESP32-S2 WiFi microcontroller, and the crispness of a 240x135 pixel color TFT display. All that and it will even plug in nicely into a breadboard, terminal block wing, or Feather Doubler or even just stack on top of another wing.

This feather comes with native USB and 4 MB flash + 2 MB of PSRAM, so it is perfect for use with CircuitPython or Arduino with low-cost WiFi. Native USB means it can act like a keyboard or a disk drive. WiFi means its awesome for IoT projects. And Feather means it works with the large community of Feather Wings for expandability.

The ESP32-S2 is a highly-integrated, low-power, 2.4 GHz Wi-Fi System-on-Chip (SoC) solution that now has built-in native USB as well as some other interesting new technologies like Time of Flight distance measurements. With its state-of-the-art power and RF performance, this SoC is an ideal choice for a wide variety of application scenarios relating to the Internet of Things (IoT), wearable electronics, and smart homes.

Please note the Feather ESP32-S2 has a single-core 240 MHz chip, so it won't be as fast as ESP32's with dual-core. Also, there is no Bluetooth support. However, we are super excited about the ESP32-S2's native USB which unlocks a lot of capabilities for advanced interfacing! This ESP32-S2 mini-module we are using on the Feather comes with 4 MB flash and 2 MB PSRAM so you can buffer massive JSON files for parsing!

The color TFT is connected to the SPI pins, and uses additional pins for control that are not exposed to the breakout pads. It's the same display as you see here, with 240x135 pixels and is IPS so you get bright color at any angle. The backlight is also connected to a separate pin so you can PWM the backlight up and down as desired.

For low power usages, the Feather has a second AP2112 regulator. The regulator is controlled with a GPIO pin on the enable line and can shut off power to the Stemma QT port and TFT. There is also a separate power pin for the NeoPixel that can be used to disable it for even lower quiescent power. With everything off and in deep sleep mode, the TFT feather uses about 100uA of current.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
