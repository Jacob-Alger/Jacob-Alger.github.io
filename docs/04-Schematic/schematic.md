---
title: Schematic
---

## Overview

This schematic is designed to support a light sensor that detects the amount of sunlight the plant receives and alerts the user if the plant is not receiving sufficient light. The schematic includes a regulated power supply, a Wheatstone bridge LDR sensor, and the microcontroller, which will send a signal when the plant needs more sunlight. The power supply regulates a 9V wall power supply to a linear 5V to be used throughout the rest of the schematic. The sensor portion utilizes a Wheatstone bridge consisting of the LDR, potentiometer, and two balancing resistors to generate a steady voltage difference. This is then amplified by the operational amplifier and sent to the transistor, which acts as an NPN switching transistor, sending either a high or low digital signal to the microcontroller. The microcontroller will then read this signal, and when it is low, it will send a converted analog signal to my teammates' boards to be interpreted and acted upon. This connection is made using an 8-pin ribbon connector, as shown in the schematic. The schematic also contains several extra connectors for debugging, corrections, and test points. This subsystem meets the user's needs by providing an accurate reading of the sensor using a balanced Wheatstone bridge and will assist the user with reliable alerts about the plant's light needs. 
The schematic is shown in **Figure 1** below, and the PDF/ZIP files are available in the *Resources* section below.
<br>



![schematic](subsystem_schematic-rev4.png){style width:"350" height:"300;"}
**Figure 1:** Light Sensor Subsystem Schematic.


## Resouces

The schematic as a PDF download is available [*here*](subsystem_design.pdf), and the Zip folder of the project [*here*](subsystem_design-rev4.zip).
