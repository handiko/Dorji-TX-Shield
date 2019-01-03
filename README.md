# Dorji-TX-Shield (v.1.0)
Dorji DRA818V VHF transmitter module shield for Arduino UNO &amp; compatibles.
This Arduino shield is intended to used as APRS Transmitter module based on Arduino UNO (see https://github.com/handiko/Arduino-APRS).

## Pinout
|Arduino Pins|Dorji DRA818V    |   Shield    |
|:----------:|:---------------:|:-----------:|
| +5V        | +VBAT           | LED 2 (PWR) |
| RESET      | -               | RESET Button|
| PIN 5      | H/L             | -           |
| PIN 6      | PD              | -           |
| PIN 7      | PTT(Active High)| -           |
| PIN 8      | <---GPS Data    | -           |
| PIN 9      | --->GPS Data    | -           |
| PIN 10     | --->Dorji Data  | -           |
| PIN 11     | <---Dorji Data  | -           |
| PIN 12     | Audio TX        | -           |
| PIN 13     | PTT LED         | -           |

_Please note that using PIN 8-11 as Serial Data lines require using **SoftwareSerial** library._

## Gerber View
* TOP Layer

![alt text](https://github.com/handiko/Dorji-TX-Shield/blob/master/Pics/gerber_top.png)

* BOTTOM Layer

![alt text](https://github.com/handiko/Dorji-TX-Shield/blob/master/Pics/gerber_bottom.png)

## TODO
* Adding Silkscreen layer
* Adding ISP port capability
* Adding RX capability (maybe in different repo..?)
* ...

## Acknowledgements
* Djoko Marjono Susilo - YB1TJ
* Adafruit Proto Shield PCB https://github.com/adafruit/Adafruit-Proto-Shield-PCB
