# LED Controller PCB

This repository contains a schematic and board layout for a WS2812B control board, based around the [Adafruit Huzzah Breakout](https://www.adafruit.com/product/2471) ESP8266 module.

The [Eagle](https://www.autodesk.com/products/eagle/overview) design files can be found in the `design` directory.

## Parts List

| Schematic Symbol | Description                   | Part Number              |
|------------------|-------------------------------|--------------------------|
| J1               | 5V 5A DC Barrel Jack          | Cliff DC10A / DC10L      |
| J2               | 3.5mm pitch terminal block    | CamdenBoss CTBP3051/3    |
| R1               | 150Ω Resistor (0805 package)  |                          |
| C1               | 3300µF Capacitor (16mm pitch) |                          |
| U$1              | Adafruit Huzzah Breakout      | Adafruit product ID 2471 |

I recommend you use 2x10 female pin headers with 2.54mm pitch to allow you to remove the [Adafruit Huzzah](https://www.adafruit.com/product/2471) without de-soldering.  Additionally, you may use 4x M2.5 screws to mount the PCB.

## Schematic

![Schematic](https://raw.githubusercontent.com/squarefrog/led-controller/documents/schematic.png)

## Layout

![Layout](https://raw.githubusercontent.com/squarefrog/led-controller/documents/board.png)

## Gerbers

Pre-generated Gerber files are available in the `gerbers` directory. This will let you upload them to your preferred PCB fabricator to get a PCB made.

## Software

For the software, please see the [software repository](https://github.com/squarefrog/led-controller-software).

## License

Cern OHL v1.2. See [LICENSE](LICENSE) file.
