# Nu-Link2-Pro_Offline_ISP 
Nu-Link2-Pro_Offline_ISP is a sample project based on KEIL uVision, that can do ISP function in Nu-Link2-Pro offline mode.  

### About how to build code and do the configuration, please check "Nu-Link2-Pro_Offline_ISP.PPT"

### operation steps
1. Build and program Nu-Link2-Pro_Offline_ISP firmware to Nu-Link2-Pro board
1. Pop up a USB disk, format it
1. Put isp.lua and test.bin into the USB disk
1. Configure target chip to boot from LDROM with LDROM ISP code. LDROM code can be found in BSP, e.g. [M480 BSP link](https://github.com/OpenNuvoton/M480BSP/tree/master/SampleCode/ISP)

1. Connect bus between Nu-Link2-Pro and target board (e.g. UART CON6 pin1 and pin2 to target board UART, share the ground)
1. Press SW1 button of Nu-Link2-Pro, then press RESET button of target board, and it will connect and programming
1. Print log from CON4 UART, the progress will be shown


