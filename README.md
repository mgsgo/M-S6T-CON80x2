## M-S6T-CON80x2

# Power of low cost FPGA.

Spartan6 TQ144 video interface board.<p>

- Xilinx XC6S-TQ144 FPGA
- FTDI FT2232 USB to JTAG/UART interface
  - no PROM
- Power input : USB 5V or DC jack 12V input
- Dual CON80 intetface
  - DVP image sensor input
    - MT9V034, MT9M031, AR0330CS, MT9M001, OV2640
  - MIPI image sensor input
    - IMX219, OV5640, AR0330CM
  - HiSPI image sensor input
    - AR0330CM
  - LVDS image sensor input
    - Onsemi PYHTON
  - OpenLDI(CAMLINK) interface
    - 1,2,3 tap base
    - 4,6,8,10 tap medium, full
  - TMDS(DVI, HDMI) interface
    - 1080p 60Hz
  - USB3.0 interface
    - CYUSB3014
    -FT602Q
- Pin map
  |01| GND |02| GND |
  |--|-----|--|-----|
  |03| D0-0|04| D1-0|
  |05| D0-1|06| D1-1|
  |07| GND |08| GND |
  |09| D0-2|10| D1-2|
  |11| D0-3|12| D1-3|
  |13| GND |14| GND |
  |15| RSTN|16| RSTN|
  |17| PCLK|18| PCLK|
  |19| GND |20| GND |
  |21| D0-4|22| D1-4|
  |23| D0-5|24| D1-5|
  |25| GND |26| GND |
  |27| D0-6|28| D1-6|
  |29| D0-7|30| D-17|
  |31| GND |32| GND |
  |33|HSYNC|34|HSYNC|
  |35|VSYNC|36|VSYNC|
  |37| GND |38| GND |
  
