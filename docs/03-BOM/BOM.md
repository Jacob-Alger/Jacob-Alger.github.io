---
title: Bill of Materials
tags:
- tag1
- tag2
---

## Overview
Below is the bill of materials for my entire light sensor subsystem PCB design, as shown in **Table 1**. Most of the parts can either be sourced in Peralta 109/103 or are in stock for ordering through Digi-Key. The pin headers and jumpers are to be used for debugging errors in my PCB design by separating sections manually and using female-to-female jumper cables where needed. The test points will be pads on the board, rather than physical parts, to remove clutter and maintain my budget.

The total cost of this BOM is \$8.35, but I'm ordering 3 extra of each major component from Digi-Key, so my total price is \$27.28, well within the $60 per team member budget established by the course requirements.

## Bill of Materials

*Table 1: BOM for Light Sensor Subsystem*
<br>


| **Part Name/Description** | **Qty** | **Unit Cost** | **Total Cost** | **Manufacturer** | **Manufacturer #** | **Supplier** | **Vendor Link** | **Datasheet Link** | **Schematic Reference Designators** |
|----------------------|----------|------------------|--------------------|--------------|-------------------|---------|------------|----------------|-------------------------------|
| Barrel Jack Connector | 1 | $0.76 | $0.76 | Same Sky | PJ-102AH | Digi-Key | [Link](https://www.digikey.com/en/products/detail/cui-devices/PJ-102AH/408448) | [Datasheet](https://www.cuidevices.com/product/resource/pj-102ah.pdf) | J1 |
| Linear Voltage Regulator | 1 | $0.75 | $0.75 | MCC | MC7805CT-BP | Digi-Key | [Link](https://www.digikey.com/en/products/detail/mcc-micro-commercial-components/MC7805CT-BP/804682) | [Datasheet](https://www.mccsemi.com/pdf/Products/MC7805CT(TO-220).pdf) | U1 |
| Op-Amp | 1 | $0.50 | $0.50 | Microchip Technology | MCP6002-E/P | Digi-Key | [Link](https://www.digikey.com/en/products/detail/microchip-technology/MCP6002-E-P/683196) | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP6001-1R-1U-2-4-1-MHz-Low-Power-Op-Amp-DS20001733L.pdf) | U2 |
| NPN Transistor | 1 | $1.70 | $1.70 | Diotec Semiconductor | 2N2222A | Digi-Key | [Link](https://www.digikey.com/en/products/detail/diotec-semiconductor/2N2222A/13164037) | [Datasheet](https://diotec.com/request/datasheet/2n2222a.pdf) | Q1 |
| Photoresistor | 1 | $0.87 | $0.87 | Advanced Photonix | NSL-5152 | Digi-Key | [Link](https://www.digikey.com/en/products/detail/advanced-photonix/NSL-5152/5423680) | [Datasheet](https://www.advancedphotonix.com/wp-content/uploads/2015/07/DS-NSL-5152.pdf) | R5 |
| Potentiometer | 1 | $3.77 | $3.77 | Bourns Inc. | 3310R-125-103L | Digi-Key | [Link](https://www.digikey.com/en/products/detail/bourns-inc/3310R-125-103L/2537840) | [Datasheet](https://www.bourns.com/docs/Product-Datasheets/3310.pdf) | RV1 |
| 8-pin DIP IC Socket | 1 | $0.00 | $0.00 | Assmann WSW Components | A 08-LC-TT | Peralta | [Link](https://www.digikey.com/en/products/detail/assmann-wsw-components/A-08-LC-TT/821740) | [Datasheet](http://www.assmann-wsw.com/uploads/datasheets/ASS_0810_CO.pdf) | U2 |
| .1 uF, 50V Capacitor | 5 | $0.00 | $0.00 | Vishay Beyschlag/Draloric/BC Components | K104K10X7RF5UH5 | Peralta | [Link](https://www.digikey.com/en/products/detail/vishay-beyschlag-draloric-bc-components/K104K10X7RF5UH5/2356879) | [Datasheet](https://www.vishay.com/docs/45171/kseries.pdf) | C2, C3, C4, C5, C6 |
| 10 uF, 50V Capacitor | 1 | $0.00 | $0.00 | Lumimax Optoelectronic Technology | MC2-1206Y106M500BF3 | Peralta | [Link](https://www.digikey.com/en/products/detail/lumimax-optoelectronic-technology/MC2-1206Y106M500BF3/16735086) | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/7152/%5BLumimax%5DMonoCap%20GP%20Series.pdf) | C1 |
| 1k, 1/4W Resistor | 1 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | R1 |
| 200k, 1/4W Resistor | 1 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | R2 |
| 10k, 1/4W Resistor | 4 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | R3, R4, R7, R8 |
| 4.7k, 1/4W Resistor | 1 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | R6 |
| 300, 1/4W Resistor | 1 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | R9 |
| 1A Fuse 5x20 | 1 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | F1 |
| 2-pin Jumper | 16 | $0.00 | $0.00 | n/a | n/a | Peralta | n/a | n/a | J2, J3, J4, J5, J6, J7, J8, J9, J10, J11, J12, J13, J14, J15, J17, J18 |
| 40 Pin Header Connector | 2 | $0.00 | $0.00 | Lystaii | n/a | Peralta | [Link](https://www.amazon.com/Header-Lystaii-Pin-Connector-Electronic/dp/B06ZZN8L9S/ref=sr_1_15?dchild=1&keywords=40+pin+header+male+to+male&qid=1608606507&sr=8-15) | n/a | J2, J3, J4, J5, J6, J7, J8, J9, J10, J11, J12, J13, J14, J15, J17, J18, J16, J19, J20, J21 |
| 40 Pin 2.54mm Single Row Straight Female PCB Header | 2 | $0.00 | $0.00 | Qunqi | n/a | Peralta | [Link](https://www.amazon.com/Qunqi-2-54mm-Straight-Connector-Arduino/dp/B07CGGSDWF/ref=sr_1_17?dchild=1&keywords=female+header+strips&qid=1595380282&sr=8-17) | n/a | U3 |
| Red LED | 1 | $0.00 | $0.00 | n/a | n/a | Kit | n/a | n/a | D1 |
| Pushbutton Switch | 1 | $0.00 | $0.00 | n/a | n/a | Kit | n/a | n/a | SW1 |


<br>
