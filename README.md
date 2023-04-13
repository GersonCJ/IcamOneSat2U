# IcamOneSat2U
Projet Majeur Semetre I4.8 -Icam/CNES

## Objective
<p>This project's porpose is the developpement, dimensioning and assembling of a CubeSat <br>(A miniaturized Satellite with a cubic form factor).<p>

<p><img src="./assets/images/cubesat.png"><p>

<p>Contrarily to traditional CubeSats, this particular one won't be launched to space. It's a simpler version designed to be attached to a ballon and travel <em> some distance</em> while capting and transmitting information such as temperature, pression, coordinates, etc...<p>

<p>The following sections are meant to go deeper into the project's developement and organisation.<p>

## Table of Contents
<ol>
    <li>List of components provided</li>
    <li>Informations related to MCU - mbed NXP LPC1768
</ol>

### List components provided

|    | Component                     |   Quantities |
|---:|:------------------------------|-------------:|
|  0 | 470ohm Resistor               |            7 |
|  1 | 1,2kohm Resistor              |            1 |
|  2 | 2kohm Resistor                |            3 |
|  3 | 15kohm Resistor               |            5 |
|  4 | 10ohm Resistor                |            3 |
|  5 | 10kohm Resistor               |            1 |
|  6 | 22kohm Resistor               |            1 |
|  7 | 10mH Inductor                 |            1 |
|  8 | 330ohm Resistor               |            1 |
|  9 | 32.4kohm Resistor             |            2 |
| 10 | button                        |            1 |
| 11 | LED                           |            9 |
| 12 | Film Capacitor - MKT370       |            2 |
| 13 | Temperature Sensor - DS18B20  |            4 |
| 14 | Lora Wireless Stick Lite      |            2 |
| 15 | Antenna                       |            1 |
| 16 | Barometric Sensor - MPL3115A2 |            1 |
| 17 | Light Sensor - ALSPT19        |            5 |
| 18 | GPS - NEO-M9N-00B             |            1 |
| 19 | Gyroscope - BNO055            |            1 |
| 20 | MCU mbed NXP LPC1768          |            1 |
| 21 | Camera Module - SBC-ESP32-CAM |            1 |

### Informations related to MCU - mbed NXP LPC1768
<ul>
    <li>[Home Page](https://os.mbed.com/platforms/mbed-LPC1768/#firmware)</li>
    <li>[Documentation](https://os.mbed.com/docs/mbed-os/v6.16/introduction/index.html)</li>
    <li>[Arm Keil Studio Cloud - User Guide](https://developer.arm.com/documentation/102497/1-5/Tutorials/Work-with-Git-source-control/Use-source-control-and-publish-your-changes)</li>
    <li>Attention! Serial Ports may not be recognized on windows, thus serial communication with softwares such as Putty may not work. Recommended using Unix derived OS.</li>
</ul>
