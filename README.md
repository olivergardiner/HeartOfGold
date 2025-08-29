# HeartOfGold
Open hardware implementation of a Tube Driver

https://whitecottage.org.uk/pedals/the-heart-of-gold/

This version is a subtantial revamp using EasyEDA and SMT devices. Key features of the new design include:
* Only requires a standard 9v pedal power supply (must be able to deliver 500mA, though)
* Uses the Big Muff tone stack and moves the bias control into main controls
* Highly configurable (using jumpers) to support a wide range of circuit variants, including the patented version

In contrast to the version with the 12V AC supply, this version uses a single rail and a virtual ground at the rail's mid-point. The positive supply rail is provided by a boost converter that allows the rail to be set to any of 24V, 18V, 12V or 9V.

The heaters connected are in parallel and can also be configured for the 6N2P. The default heater voltage is 6.3V but it can be dropped to 4.5V (equivalent to the patented version with series heaters fed by 9V).

The coupling capacitance from the gain stage to the first tube can be doubled which halves the high-pass pole to around 350Hz, which is close to the patented version.

The plate load of each tube can be adjusted to match the common versions - 68K and 47K for V1 and 100K, 68K and 47K for V2.

Finally, the grid bias of the second tube can be wired to either ground (modern versions) or B+ (patented version)
