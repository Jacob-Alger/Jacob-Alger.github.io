---
title: Resources
---

## Overview
For my PCB to function as a light sensor, I programmed the board to check the analog voltage from the op-amp, as illustrated in my block diagram. The code features a loop that checks the value. If the value is near the maximum, it waits 2 seconds to verify that the signal is high. Then, it both lights the LED and sends a digital high signal to the ribbon connector pin to communicate with my teammate's speaker board. It also features an if statement to use the debugging switch to manually light the LED for testing purposes. This code is not the most efficient, as it is constantly stalled. In future projects, I plan to use interrupts and global timers to perform these processes more efficiently. However, given my current skill level and the complexity of the subsystem, the following code works. The project was made by Microchip's IDE, MPLAB X IDE, to program the Curiosity Nano Board. The project can be found below in the *Resources* Section

## Resources
The MPLAB X IDE project can be downloaded as a ZIP folder [here](subsystem-design.zip).

