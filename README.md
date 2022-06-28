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
  |03| A-D0|04| D1-0|
  |05| A-D1|06| D1-1|
  |07| GND |08| GND |
  |09| A-D2|10| D1-2|
  |11| A-D3|12| D1-3|
  |13| GND |14| GND |
  |15| A-RSTN|16| RSTN|
  |17| A-PCLK|18| PCLK|
  |19| GND |20| GND |
  |21| A-D4|22| D1-4|
  |23| A-D5|24| D1-5|
  |25| GND |26| GND |
  |27| A-D6|28| D1-6|
  |29| A-D7|30| D-17|
  |31| GND |32| GND |
  |33| A-HSYNC|34|HSYNC|
  |35| A-VSYNC|36|VSYNC|
  |37| GND |38| GND |
  |39| A-SCL
  |41| A-SDA
  |43| 3V3
  |45| MCLK/VCCIO
  |47| GND
  |49| C-D0
  |51| C-D1
  |53| GND
  |55| C-D2
  |57| C-D3
  |59| GND
  |61| C-RSTN
  |63| C-PCLK
  |65| GND
  |67| C-D4
  |69| C-D5
  |71| GND
  |73| C-D6
  |75| C-D7
  |77| GND
  |79| 12V
