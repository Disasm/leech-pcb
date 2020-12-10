# Leech

An extension board with iCE40UP5k for the STM32F411 "Black Pill" board.

This project is based on the [icepill] project by [Adam Greig].
Some of the footprints were also taken from the icepill project.

![PCB render](render.png)
![PCB photo](pcb_photo.jpg)

| iCE40  | STM32 | Notes
|--------|-------|------
| 16     | PB12  | SPI SS
| 15     | PB13  | SPI SCK
| 14     | PB14  | SPI MISO
| 17     | PB15  | SPI MOSI
| 20     | PA8   | Clock for iCE40 provided by MCO
| 13     | PA9   |
| 12     | PA10  |
| 11     | PA11  |
| 10     | PA12  |
| 6      | PA15  |
| 3      | PB3   |
| 2      | PB4   |
| 48     | PB5   |
| 47     | PB6   |
| 46     | PB7   |
| 45     | PB8   |
| 44     | PB9   |
|        |       |
| 18     | PB10  | Used for IRQ
| CRESET | PB2   | This line is pulled down by the main board
| 25     | PB1   |
| 26     | PB0   |
| 27     | PA7   |
| 28     | PA6   |
| 34     | PA5   |
| 35     | PA4   |
| 36     | PA3   |
| 37     | PA2   |
| 38     | PA1   |
| 42     | PA0   | Connected to a button on the main board
| 43     | RESET |

Firmware and gateware: https://github.com/Disasm/leech-fw

This schematic and PCB design are licensed under the
Creative Commons [CC0 public domain dedication].
It is provided with no warranty.

[icepill]: https://github.com/adamgreig/icepill
[Adam Greig]: https://github.com/adamgreig
[CC0 public domain dedication]: https://creativecommons.org/publicdomain/zero/1.0/

## Revision History

### 1.2: 2020-11-13

* First version.
* Errata:
    * Drill diameter of 2.54mm connector pads is too small.
