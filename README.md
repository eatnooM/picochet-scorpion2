# Picochet-Scorpion2

A dedicated microcontroller board for use with the OpenFIRE firmware, made to fit in the wonderfully comfortable Blaze Scorpion 2 shell

Picking up where the Picochet-TC1 left off, this board removes the solenoid feedback circuit and adds support for a few extra goodies that might make sense to add in a Scorpion 2, such as Neopixel LED (I have a 3D printable light pipe that takes the place of one of the wheels to adjust the laser in the stock Scorpion 2) and an analog stick (no plans to physically accommodate this in the shell but if you reckon you can make one fit, go nuts)

##  BOM

|                  Reference                 |    Part desc / number    | Quantity |                               Notes                               |
|--------------------------------------------|--------------------------|----------|-------------------------------------------------------------------|
| C1,C5,C19,C21                              | 10uF 0805 - [LCSC](https://www.lcsc.com/product-detail/C95841.html)          | 4        |                                                                   |
| C6,C7,C9,C10                               | 4.7uF 0402 - [LCSC](https://www.lcsc.com/product-detail/C23733.html)         | 4        |                                                                   |
| C8,C11,C12,C13,C14,C15,C16,C17,C18,C20 | 0.1uF 0402 - [LCSC](https://www.lcsc.com/product-detail/C307331.html)         | 10       |                                                                   |
| C3,C4                                      | 15pF 0402 - [LCSC](https://www.lcsc.com/product-detail/C86285.html)          | 2        |                                                                   |
| D1                                         | SOD-323F Schottky - [LCSC](https://www.lcsc.com/product-detail/C552826.html)  | 1        |                                                                   |
| D2                                         | RBR3LAM60B - [LCSC](https://www.lcsc.com/product-detail/C509954.html)         | 1        |                                                                   |
| F1                                         | PPTC-6V 500mA - [LCSC](https://www.lcsc.com/product-detail/C269104.html)      | 1        |                                                                   |
| L1                                         | AOTA-B201610S3R3 - [LCSC](https://www.lcsc.com/product-detail/C42411119.html)   | 1        |                                                                   |
| Q1                                         | DMT12H060LFDF - [LCSC](https://www.lcsc.com/product-detail/C5711753.html)      | 1        |                                                                   |
| R2,R4,R6,R14,R16                           | 1K 0402 - [LCSC](https://www.lcsc.com/product-detail/C11702.html)            | 5        |                                                                   |
| R15,R17                                    | 100K 0402 - [LCSC](https://www.lcsc.com/product-detail/C60491.html)          | 2        |                                                                   |
| R5                                         | 33Ω 0402 - [LCSC](https://www.lcsc.com/product-detail/C138002.html)           | 1        |                                                                   |
| R7,R8                                      | 27Ω 0402 - [LCSC](https://www.lcsc.com/product-detail/C138021.html)           | 2        |                                                                   |
| U1                                         | RP2354A - [LCSC](https://www.lcsc.com/product-detail/C41378174.html)            | 1        |                                                                   |
| U2                                         | NCP1117-3.3_SOT223 - [LCSC](https://www.lcsc.com/product-detail/C26537.html) | 1        |                                                                   |
| Y1                                         | ABM8-272-T3 - [LCSC](https://www.lcsc.com/product-detail/C20625731.html)        | 1        |                                                                   |
| SW1,SW2                                         | 4x3mm push button - [LCSC](https://www.lcsc.com/product-detail/C455280.html)        | 2        |                                                                   |

Optional components (see Notes): 
|                  Reference                 |    Part desc / number     | Quantity |                               Notes                               |
|--------------------------------------------|---------------------------|----------|-------------------------------------------------------------------|
| C24   | 0.1uF 0805 - [LCSC](https://www.lcsc.com/product-detail/C1711.html)         | 1        | Installation not recommended                                      |



## Thanks

OpenFIRE project - https://openfirelightgun.org/
