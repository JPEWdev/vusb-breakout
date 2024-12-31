# vusb-breakout
KiCAD PCB design for a V-USB breakout board

This breadboard compatible board has all the components required for a
[V-USB][1] based project, suitable for connecting directly to the pins of an
Atmel.

Features include:

1. Voltage limiting Zener diodes on D+ and D- so the Atmel can be run anywhere
   between 3.3 and 5 V
2. Ability to be powered from USB (if jumper is set) and/or external power (via
   Vin pin). Schottky diodes prevent back-power in both cases.
3. USB ID pin is broken out

NOTE: If running the Atmel at 5V, the board will draw about 20 mA from either
D+ or D- when they are driven high.

[1]: https://www.obdev.at/products/vusb/index.html
