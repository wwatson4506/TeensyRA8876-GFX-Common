# TeensyRA8876-GFX-Common
## A universal RA8876 graphics library for use with SPI and 8080 drivers for Teensy boards and variants.

Communication with the Teensy is accomplished using a 3/4 wire interface.

![https://github.com/wwatson4506/TeensyRA8876-GFX-Common/blob/main/extras/RA8876_GFX_Common.jpg](https://github.com/wwatson4506/TeensyRA8876-GFX-Common/blob/main/extras/RA8876_GFX_Common.jpg)

This library is designed for use  with one of the following RA8876 drivers:

- https://github.com/wwatson4506/TeensyRA8876-8080
or:
- https://github.com/wwatson4506/TeensyRA8876-SPI

***
## LIBRARY INSTALLATION
1. Unzip **TeensyRA8876-GFX-Common** into the **Arduino/libraries**  folder.
2. Unzip **TeensyRA8876-8080** or **TeensyRA8876-SPI** into the **Arduino/libraries** folder.
3. Download **ILI9341_fonts** [https://github.com/wwatson4506/ILI9341_fonts](https://github.com/wwatson4506/ILI9341_fonts) and install into the **Arduino/libraries** folder.
***

### PINOUTS
Pinouts are defined in the driver libraries.
***
### CONFIG FILES
Both 8080 Parallel and SPI libraries have a config file.
Config files for 8080 and SPI are found in the driver libraries.
***

### EXAMPLES
Are found in the driver libraries.
***

# CREDITS
Major work on this library was done by the following PJRC forum members:

@mjs513, @KurtE, @MorganS, @rezo and @K7MDL (Keith).

They added functions to be compatible with other display libraries, performed a major rework and helped in debugging the code. The 8080 parallel FlexIO driver is based on work done by @rezo.

***

# REFERENCES
ER-TFTM-101-1 10.1" TFT from BuyDisplay:
- https://www.buydisplay.com/serial-spi-i2c-10-1-inch-tft-lcd-module-dislay-w-ra8876-optl-touch-panel
- https://www.buydisplay.com/download/ic/RA8876.pdf

PJRC Forum Threads:
- https://forum.pjrc.com/threads/58565-RA8876LiteTeensy-For-Teensy-T36-and-T40
- https://forum.pjrc.com/index.php?threads/ra8876-parallel-display-library-testing.75345/
- https://forum.pjrc.com/index.php?threads/recommendations-for-10-tft-display-with-touchscreen-for-teensy-4-1.75666/
***

# This is WIP.  USE AT YOUR OWN RISK.  There are no guarantees when using this library. More to come.
