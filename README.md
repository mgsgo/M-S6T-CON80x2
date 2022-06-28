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
  | #| DVP    | #| DVP    | | DIFF      | DIFF      |
  |--|--------|--|--------|-|-----------|-----------|
  |01| GND    |02| GND    | |01| GND    |02| GND    |
  |03| A-D0   |04| B-D0   | |03| A-D0N  |04| B-D0N  | 
  |05| A-D1   |06| B-D1   | |05| A-D0P  |06| B-D0P  | 
  |07| GND    |08| GND    | |07| GND    |08| GND    | 
  |09| A-D2   |10| B-D2   | |09| A-D1N  |10| B-D1N  | 
  |11| A-D3   |12| B-D3   | |11| A-D1P  |12| B-D1P  | 
  |13| GND    |14| GND    | |13| GND    |14| GND    | 
  |15| A-RSTN |16| B-RSTN | |15| A-CKN  |16| B-CKN  | 
  |17| A-PCLK |18| B-PCLK | |17| A-CKP  |18| B-CKP  | 
  |19| GND    |20| GND    | |19| GND    |20| GND    | 
  |21| A-D4   |22| B-D4   | |21| A-D2N  |22| B-D2N  | 
  |23| A-D5   |24| B-D5   | |23| A-D2P  |24| B-D2P  | 
  |25| GND    |26| GND    | |25| GND    |26| GND    | 
  |27| A-D6   |28| B-D6   | |27| A-D3N  |28| B-D3N  | 
  |29| A-D7   |30| B-D7   | |29| A-D3P  |30| B-D3P  | 
  |31| GND    |32| GND    | |31| GND    |32| GND    | 
  |33| A-HSYNC|34| B-HSYNC| |33| A-PWDN |34| B-PWDN | 
  |35| A-VSYNC|36| B-VSYNC| |35| A-IO   |36| B-IO   | 
  |37| GND    |38| GND    | |37| GND    |38| GND    | 
  |39| A-SCL  |40| B-SCL  | |39| A-SCL  |40| B-SCL  | 
  |41| A-SDA  |42| B-SDA  | |41| A-SDA  |42| B-SDA  | 
  |43| `3V3`  |44| `3V3`  | |43| `3V3`  |44| `3V3`  | 
  |45| A-MCLK |46| B-MCLK | |45| A-MCLK |46| B-MCLK | 
  |47| GND    |48| GND    | |47| GND    |48| GND    | 
  |49| C-D0   |50| D-D0   | |49| C-D0N  |50| D-D0N  | 
  |51| C-D1   |52| D-D1   | |51| C-D0P  |52| D-D0P  | 
  |53| GND    |54| GND    | |53| GND    |54| GND    | 
  |55| C-D2   |56| D-D2   | |55| C-D1N  |56| D-D1N  | 
  |57| C-D3   |58| D-D3   | |57| C-D1P  |58| D-D1P  | 
  |59| GND    |60| GND    | |59| GND    |60| GND    | 
  |61| C-RSTN |62| D-RSTN | |61| C-CKN  |62| D-CKN  | 
  |63| C-PCLK |64| D-PCLK | |63| C-CKP  |64| D-CKP  | 
  |65| GND    |66| GND    | |65| GND    |66| GND    | 
  |67| C-D4   |68| D-D4   | |67| C-D2N  |68| D-D2N  | 
  |69| C-D5   |70| D-D5   | |69| C-D2P  |70| D-D2P  | 
  |71| GND    |72| GND    | |71| GND    |72| GND    | 
  |73| C-D6   |74| D-D6   | |73| C-D2N  |74| D-D3N  | 
  |75| C-D7   |76| D-D7   | |75| C-D2P  |76| D-D3P  | 
  |77| GND    |78| GND    | |77| GND    |78| GND    | 
  |79| `12V`  |80| `5V`   | |79| `12V`  |80| `5V`   | 
