# ESP32-C3FH4-RGB 

![image](https://github.com/andypiper/fivebyfive/blob/main/reference/ESP32-C3FH4-RGB-reference.jpeg)
driver


https://zadig.akeo.ie/


General Flashing Instructions:

Install driver with zadig as mentioned above.
Install Arduino IDE and install espressif resources by adding line "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json" to Additional Boards Manager URLs in Arduino IDE Files / Preferences.
Via Arduino IDE Tools/Board / Board Manager search for ESP32 and choose Espressif Systems version 2.0.2 to install it.
Install ESP32 Digital RGB LED Drivers and Adafruit NeoPixel via option tools / Manage Libraries in Arduino IDE.
Setup connection to connect to Board ESP32C3 Dev and com port which is assocuiated to USB Serial Device, not jtag (see Device Manager on Win10). Other settings see settings.png.

Upload sketch from Arduino IDE:

Hold down B button on board, press R button and release again but keep on pressing B, trigger Arduino IDE to upload sketch, keep B pressed until Arduino IDE says that it's connected. Then you can release B button.

Serial works with "CDC enable on boot" set to true.

Here is also a very cool fivebyfive code contributed by Andy piper
https://github.com/andypiper/fivebyfive

Open Source / Contributors
Origins for this fork (Thanks!):

fivebyfive (for fivebyfive),


And many many others who haven't been mentioned....
