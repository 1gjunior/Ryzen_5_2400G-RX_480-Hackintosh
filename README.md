# OpenCore Hackintosh guide for Ryzen 5 2400G, RX 480

### EFI Bootloader files to boot macOS Catalina using OpenCore on Ryzen 5 2400G, RX 480

## Working OS

Till macOS Big Sur Beta 3 (any previous OS such as Catalina will boot as well)

## What Works


- everything works fine

## Whats broken


audio still crackling

## Installation

### PS: If you are making dual boot, make sure your EFI partition is larger than 400mb+, 500~700mb is recommended 

### Set BIOS settings 
Press `F2 or DEL` to load BIOS settings. Change the following settings:

- Disk: AHCI
- UEFI Boot: Enabled
- Secure Boot: Disabled
- CSM: Disabled

1. Make bootable usb from Opencore using GibMacOS from [here](https://dortania.github.io/OpenCore-Install-Guide/installer-guide)

2. Follow the instructions, use config2.plist for booting

3. Then after following intructions, add my EFI Folder 

4. Reboot 

6. Reboot, everything should be as fine as it should be

## Some FAQ


### Q. AMD Graphics works?
A. Yes



### Guide by ©1gjunior, cherrypicked resources from various sites 
