# Little Wire Clone

This directory describes a KiCad 5.1.6 project directory for my clone of
the Little Wire project by Ihsan Kehribar.

![](pcbrender_front.png)
![](pcbrender_back.png)

## Bill of Materials

Here is an informal BOM with the parts I used for my two boards so far.
Note that some of the values don't match with the schematic; I used some parts
that I had available from previous orders where it shouldn't make too much of
a difference anyway.

| ref | amount | partno | name |
| --- | ------ | ------ | ---- |
| U1 | 1 | ATTINY85-20PU | Microchip Technology ATTINY85-20PU IC MCU 8BIT 8KB FLASH 8DIP |
| USB1 | 1 | 10118194-0001LF | Amphenol ICC CONN RCPT USB2.0 MICRO B SMD R/A |
| C1, C2 | 2 | CL21B104KACNNNC | Samsung CAP CER 0.1UF 25V X7R 0805 |
| D1, D2 | 2 | MMSZ4684T1G | ON Semiconductor DIODE ZENER 3.3V 500MW SOD123 |
| D3 | 1 | LTST-C171AKT | Lite-On Inc. LED ORANGE CLEAR SMD |
| R1, R2 | 2 | RC0805FR-07100RL | Yageo RES SMD 100 OHM 1% 1/8W 0805 |
| R3 | 1 | RC0805FR-072K2L | Yageo RES SMD 2.2K OHM 1% 1/8W 0805 |
| R4 | 1 | RC0805FR-07330RL | Yageo RES SMD 330 OHM 1% 1/8W 0805 |
| ICSP1 | 1 | SSQ-103-01-T-D | Samtec Inc. CONN RCPT 6POS 0.1 TIN PCB |

## LICENSE

Copyright (c) 2020 Anton Semjonov

This source describes Open Hardware and is licensed under the CERN-OHL-P v2

You may redistribute and modify this documentation and make products using it
under the terms of the CERN-OHL-P v2 (https:/cern.ch/cern-ohl). This
documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING
OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE.
Please see the CERN-OHL-P v2 for applicable conditions.
