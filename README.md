# ESP8266-based air quality sensor master board

This is a board that powers an ESP-12S module with USB-C, and has breakouts for I2C and UART.

![image of board](./image.png)

Designed for use as an air quality sensor in combination with:

- Sensirion SCD41 (high accuracy NDIR CO2) - available on an I2C breakout board from various manufacturers
- Sensirion SGP40 (VOC) - available on an I2C breakout board from various manufacturers
- Sensirion SPS30 (particulate matter) - Sensirion manufactures an eval kit that comes with a cable, Sparkfun also sells their own similar kit

Though there's nothing really air-quality-specific here. This is a generic board that powers an ESP-12S and breaks out the I2C/UART pins + 5v/3.3v power to headers. Whatever you connect to those headers is up to you.

See [bom.ods](./bom.ods) for LCSC part numbers for this board (for PCB assembly by JLCPCB).
