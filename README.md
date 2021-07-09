# GMT130-ESP8266
>## Connection scheme of **GMT130** IPS screen (240x240) and **ESP8266** microcontroller.

### Hardware Required:
* NodeMCU board (LoLin)
* ST7789 TFT display module (240x240)
* Micro USB cable
* Wires

<br>

#### Connect your components according to the following scheme:

![Scheme image](https://simple-circuit.com/wp-content/uploads/2019/07/esp8266-nodemcu-st7789-spi-tft-circuit.png)

<br><br>

## Before starting the coding action, don't forget to import two essential libraries.
```
#include <Adafruit_GFX.h>    // Core graphics library
#include <Adafruit_ST7789.h> // Hardware-specific library for ST7789
```
