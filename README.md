
# MP3 Player Hardware – XIAO ESP32-C6

This branch contains the open-source hardware design for a compact MP3 player built around the Seeed Studio XIAO ESP32-C6. It includes schematic-level details suitable for perfboard or custom PCB implementation.

## Hardware Overview
- Microcontroller: XIAO ESP32-C6
-  Audio Output:
   PWM-based
   RC low-pass filter with ceramic capacitor and resistor
   3.5 mm AUX jack (GND to sleeve)
   
-  Buttons:
   3x tactile push buttons (GPIO 0, 1, 2)
   
  - Display:
    0.96″ I²C OLED (SDA: GPIO 22, SCL: GPIO 23)

 - SD Card:
 SPI interface (MOSI: GPIO 7, MISO: GPIO 8, CLK: GPIO 9, CS: GPIO 10)
    
- Power:
   3.7 V LiPo pouch cell

## License

Licensed under the [MIT License](https://opensource.org/licenses/MIT)

> Based on MP3 Player Hardware by Aarik D'souza (2025)
> Please include attribution in any derivative hardware designs.
