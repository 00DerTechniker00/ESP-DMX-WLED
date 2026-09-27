# ESP-DMX-WLED
.bin for WLED with enabled DMX output for an ESP32-C3

| ESP32 C3 | MAX485 | Kabel | XLR-Buchse |
| -------- | ------ | ----- | ---------- |
| 5V (VCC) | VCC | - | - |
| GND | GND | Gesammtschirm | Pin1 |
| GPIO 21 | DI | - | - |
| 3.3V | DE + RE | - | - |
| - | A | Ader 1 | Pin 3 |
| - | B | Ader 2 | Pin 2 |

> Wichtig: Bei einem Netwekkabel ein getwistetes pärchen benutzen. (z.B. Ader 1 = Blau, Ader 2 = Weiß/Blau)

3D-Modell für die .bin:
[https://makerworld.com/en/my/models/3359192](https://makerworld.com/en/models/3359192-esp-dmx-controller-with-wled))

Original Source Code:
[https://github.com/wled/WLED](https://github.com/wled/WLED)
