# NUCLEO-H745ZI-Q_SPI_SDCARD
Example of connecting an SD-card to NUCLEO-U745ZI-Q board via SPI. <br>
<br>
Release on NUCLEO-H745ZI-Q board with FatFS + SD Card via SPI1 interface. <br>
The project generated in Cube-MX program for Keil MDK-ARM IDE. Cube-MX project inside. <br>
Added two files: fatfs_sd.c and fatfs_sd.h from https://github.com/eziya <br>
<br>
Reference : 
 - http://elm-chan.org/docs/mmc/mmc_e.html
 - https://github.com/eziya
<br>
```python

![NUCLEO-H745](https://github.com/ku100-png/NUCLEO-H745ZI-Q_SPI_SDCARD/raw/main/IMG_NUCLEO-H745-ZI.jpg) <br>
```
<br>
For connect SD-card use 6-pin dual-row header on Adafruit 1.8" TFT Shield V2. It requires 3 wires to be run
to the appropriate digital I/O pins to route SPI from the Nucleo to the the SD card. Solder them to the
free holes marked D11,D12,D13 at the top and connect then to 6-pin header to pin4, pin1 and pin3, looking up at the image.
