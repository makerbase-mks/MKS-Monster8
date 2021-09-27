# MKS-Monster8
## Hardware
  - MCU is STM32F407VET6, 168MHz, 512K flash, 192KB RAM
  - DC12-24V input(2 MP1584EN Output DC12V(For FANs) and DC5V)
  - 4 heaters + 4 temps interface(H-BED,HE0,HE1,HE2; TB, TH0,TH1,TH2)
  - 3 PWM FANs + 3 power output(all power can be select by jumper and select VIN, dc12V, dc5V)
  - 8 axis drivers and 9 motor interface(Driver0,1,2-1,2-2,3,4,5,6,7)
  - EXP1,EXP2 support [MKS MINI12864](https://makerbase.aliexpress.com/store/group/LCD/1047297_516922172.html),[MKS TS35](https://www.aliexpress.com/item/1005001446396197.html),LCD12864,LCD2004
  - USART(usart1:PA9,PA10) support [MKS H43](https://www.aliexpress.com/item/1005002008179262.html) or for other serial communication
  - 6 endstop support power select(X-,X+,Y-,Y+,Z-,Z+) and 3D TOUCH(PA8) interface
  - 4K eeprom on board(connect to I2C)
  - Built-in CAN transceiver and interface(connect to CAN)
  - Integrated SPI communication microsd card and reserved SPI signal interface 
  - Integrated UDISK
  - Integrated virtural USB device
  - Support TMC UART and SPI mode, SENSORLESS_HOMING function(Diag0-5,connect to X-,Y-,Z-,X+,Y+,Z+)
  - Support driver power select(5V or 3.3V)
  - Has TVS power spike protection
  - Support DFU mode set by button(Boot0)

## Firmware
  - Support Marlin 2.0.x
  - Support Klipper
  - Update firmware
    - DFU upload
	- TF card update
	- Udisk update

## Related tutorials and Notice
  - MKS Monster8 manual, you can refer to Wiki.[click here](https://github.com/makerbase-mks/MKS-Monster8/wiki)
  - The [marlin 2.0.x firmware](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)
  - The [Klipper firmware](https://github.com/KevinOConnor/klipper)
  - [MKS Monster8 klipper firmware bin file](https://github.com/makerbase-mks/Klipper-for-MKS-Boards/tree/main/MKS%20Monster8)

## How to buy
  - [MKS Monste8](https://www.aliexpress.com/item/1005003292898244.html)

## Note
- Thank you for using MKS products. If you have any questions during use, please contact us in time and we will work with you to solve it.
- For more product dynamic information and tutorial materials, you can always follow MKS's Facebook and GitHub and YouTube. Thank you!
![](https://github.com/makerbase-mks/MKS-Robin-Nano/blob/master/hardware/Image/MKS_FGA.png)
