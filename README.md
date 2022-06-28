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
  | #| DVP    | #| DVP    | |
  |--|--------|--|--------|-|
  |01| GND    |02| GND    | |
  |03| A-D0   |04| B-D0   |
  |05| A-D1   |06| B-D1   |
  |07| GND    |08| GND    |
  |09| A-D2   |10| B-D2   |
  |11| A-D3   |12| B-D3   |
  |13| GND    |14| GND    |
  |15| A-RSTN |16| B-RSTN |
  |17| A-PCLK |18| B-PCLK |
  |19| GND    |20| GND    |
  |21| A-D4   |22| B-D4   |
  |23| A-D5   |24| B-D5   |
  |25| GND    |26| GND    |
  |27| A-D6   |28| B-D6   |
  |29| A-D7   |30| B-D7   |
  |31| GND    |32| GND    |
  |33| A-HSYNC|34| B-HSYNC|
  |35| A-VSYNC|36| B-VSYNC|
  |37| GND    |38| GND    |
  |39| A-SCL  |40| B-SCL  |
  |41| A-SDA  |42| B-SDA  |
  |43| 3V3    |44| 3V3    |
  |45| A-MCLK |46| B-MCLK |
  |47| GND |48| GND |
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
