# MKS-Monster8-DFU
- Upload bootloader
  - Press the Boot0 button when there is no power
  - Connect USB to PC and enter DFU
  - Run: DFU-Upload-Bootloader.bat

- Update firmware
  - Press the Boot0 button when there is no power
  - Connect USB to PC and enter DFU
  - Copy your compiled the mks_monster8.bin file to DFU-Upload path
  - DFU-Upload-firmware.bat
  
- Tips: Can not be modified bootloader's or firmware's file name. Otherwise, DFU cannot be update it.

- More information refer to: https://github.com/makerbase-mks/MKS-Monster8/wiki/DFU_upload

Tip: If your board does not enter the DFU, it may be that the STM32 Bootloar driver is not installed, you can try to run zadig-2.4.exe to install the driver.