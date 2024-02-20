I²C Framework Expansion Card
============================

Non-isolated I²C master.


## Pinout

To connect to this board, one has to use a 4-pin JST XH connector. The following
table represents the pinout, pin 1 being on the left as looking into the
expansion card.

| # | Ref   | Description                     |
|--:|:-----:|---------------------------------|
| 1 | GND   | Ground connection               |
| 2 | V+    | Positive voltage                |
| 3 | SDA   | Data                            |
| 4 | SCL   | Clock                           |

Output voltage is either 3.3V or 5V at up to 100 mA. Pull-up is done to the same
level.


## LEDs

Left LED signals if serial data is received or sent.

Right LED signals if output is active and there is no fault.


---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
