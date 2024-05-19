# STM32 Development board

This project contains KiCAD project files for a custom STM32 development board PCB which uses the STM32F103C8Tx microcontroller.

## Schematic design
The PCB schematic file for development board is contained in the file `stm32_board.kicad_sch`. The following is a screenshot of the schematic. 

![Schematic](assets/sch_img.png)

The development board uses the `STM32F103C8Tx` microcontroller. USB interface is used for both power supply and serial communication. The power fdrom the USB interface is regulated to +3.3V using the regulator circuit. An High Speed External clock is used for 16 MHz operation. The board includes pin header ports for UART and I2C communication also.