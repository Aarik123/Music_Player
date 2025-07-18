# Minimal MP3 Player using XIAO ESP32-C6

This project is a lightweight MP3 player built around the Seeed Studio XIAO ESP32-C6. Audio is played through PWM and filtered using a passive RC low-pass circuit to drive a stereo AUX output. The interface uses three GPIO-connected buttons for playback control.

## Features
- MP3 audio playback using PWM output
- Three-button interface: play/pause, next, previous
- RC low-pass filter for analog output
- Stereo AUX output via GPIO 22 (Left) and GPIO 23 (Right)
- Powered by a 3.7V LiPo pouch cell
- Minimal hardware and low power usage

## Hardware
- XIAO ESP32-C6 microcontroller
- MicroSD card reader (SPI interface)
- Three tactile pushbuttons (GPIO 0, 1, 2)
- RC filter (resistor + ceramic capacitor)
- Stereo 3.5mm TRRS jack
- 3.7V LiPo battery
- Solid-core wire for connections

## License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute the work, provided that original credit is given to Aarik D’souza.
