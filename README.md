# super-expander
What if ATtiny85 has 512 IO pins...

There is a cheap Chinese 16-bit IO Expander chip called AW9523B. 4 of these could be put on the same I2C bus.

With one 8-channel I2C switch PCA9548, you can put 32 AW9523B together, resulting in *32x16 = 512 IO pins*

Experiment on very dense PCB routing, busy I2C bus, new 4 layers PCB promotion on JLCPCB, and my skill to solder QFN/0402 packages.
