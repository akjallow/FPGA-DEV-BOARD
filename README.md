## FPGA DSP SYSTEM-ON-MODULE

A custom FPGA system-on-module designed around the Xilinx-7000 SOCs( 400 pin BGA Package) for DSP applications.
Implements Dual DDR3L ICs in a fly-by topology , Gigabit Ethernet, USB High-speed , FTDI , QSPI Flash and EMMC persistent storage.
The Board is designed for reliable High-Speed operations by applying Controlled-Impedance Stack-Up design , strict Length-Matched Routing and Return-Path management.

## TOP VIEW
<img width="656" height="355" alt="FPGA_DSP-DEVBOARD-1" src="https://github.com/user-attachments/assets/63d17017-3a7e-44d5-b72b-b0eb143e7e9b" />

### BOTTOM VIEW
<img width="656" height="355" alt="FPGA_DSP-DEVBOARD-0" src="https://github.com/user-attachments/assets/3324436c-8cc5-4aac-9645-53119346de3f" />

### LAYOUT(TOP)
<img width="656" height="355" alt="image" src="https://github.com/user-attachments/assets/a252e542-14d3-4d4e-b709-75c2f50cb68f" />

### LAYOUT(BOTTOM)
<img width="656" height="355" alt="image" src="https://github.com/user-attachments/assets/dfbe1dbd-ef03-485b-b297-74668c3a94b1" />

## Key Features

#### Processor:
Xilinx 7000 series FPGA [XC7Z010-2CLG400I](https://www.digikey.in/en/products/detail/amd/XC7Z010-2CLG400I/3925757)
#### PCB Stack-Up : 
1-Signal / 2-GND / 3-PWR / 4-Signal / 5-GND /
6-Signal / 7-GND / 8-Signal / 9-GND / 10-Signal.
#### OTHER COMPONENTS:
- DDR3 LOW-POWER SDRAM [MT41K256M16TW-107:P](https://www.digikey.in/en/products/detail/micron-technology-inc/MT41K256M16TW-107-P/5956623) 96-Pin BGA Package.
- EMMC 4GB Persistent Storage [S40FC004C1B2I00000](https://www.mouser.in/ProductDetail/SkyHigh-Memory/S40FC004C1B2I00000?qs=OlC7AqGiEDmWmI7w2huuXw%3D%3D&srsltid=AfmBOopa-qXIfMHvtTR_5AWZUfZLI4wtNtFcMAl9Gwron8jyHMjoyrsx)
 153-pin BGA Package.
- QSPI Flash [W25Q128JVEIQ](https://www.digikey.in/en/products/detail/winbond-electronics/W25Q128JVEIQ/6819667) 
- USB-C Programming Interface
- FTDI Bridge [FT2232HL-REEL](https://www.digikey.in/en/products/detail/ftdi-future-technology-devices-international-ltd/FT2232HL-REEL/1986053) for USB-JTAG and USB-UART.
- Gigabit Ethernet using [RTL8211F-CG](https://www.lcsc.com/product-detail/C187932.html) PHY-Layer and [HR911130A](https://www.lcsc.com/product-detail/C54408.html) RGMII Jack.
- Board-to-Board Mezanine Connectors
- Switching Regulator [SY8003ADFC]( https://www.lcsc.com/product-detail/C178236.html) for :
   +1V35 DDRL power; +1V0,+3V3 and +1V8 for the FPGA and other peripherals.
