# Bourgeon - A fully open source SBC based on i.MX6Q

Bourgeon is a single board computer based on [i.MX6Q](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-6-processors/i-mx-6quad-processors-high-performance-3d-graphics-hd-video-arm-cortex-a9-core:i.MX6Q), a quad-core arm cortex A9 processor with 2Go of DDR3 RAM.
This project has been realised for learning purposes only.

_**A developpement board is functionnal, after applying hardware patches.**_

![bourgeon](img.png)

## Hardware specification

#### Connectivity :
- 2 USB type A ports
- 1 USB type C OTG port 
- 1 RJ45 10/100/1000 BASE-T ethernet
- 1 M.2 SATA connector 
- 1 SD card slot
- 1 HDMI port
- 1 GPIO raspberry pi compatible connector
- 1 USB type C debug and power port
- 1 mPCIe (with sim card available)
- 1 audio jack 3.5mm
- M.2 non-standard board to board connector, with UART, CAN, SPI, eMMC 8bits, I2C, GPIO...

#### Included memory :
- 8MB Flash NOR via SPI
- 64kB Eeprom via I2C
- 2GB DDR3 RAM 64 bits

## Software

#### Boot

This board uses [u-boot](https://www.denx.de/project/u-boot/), the sources files will be available in src/uboot.


#### linux kernel

The entire board image is under development, and not all hardware is currently supported.

Working and tested :
- RAM
- Sata
- mPCIe
- USB Host
- USB debug
- SD card slot
- Ethernet (but not standard)
- And some miscellaneous function like DVFS, etc...

#### Complete Image

A complete image can be found at img/
