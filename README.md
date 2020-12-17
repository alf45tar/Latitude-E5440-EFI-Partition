# Latitude E5440 EFI Partition

A fully working and totally stable OpenCore EFI partition to boot macOS Big Sur (11.1) or macOS Catalina (10.15.7) in your Dell Latitude E5440 (Haswell).

## Working
  - GPU (Intel HD Graphics 4400 1536MB)
  - HDMI (external monitor)
  - LAN (Intel on-board LAN adapter)
  - WIFI (Dell DW 1510 based on Broadcom BCM4322 802.11a/b/g/n)
  - USB (left and right USB 3.0 ports, rear USB 2.0 port)
  - SATA HD or SSD, mSATA SSD
  - SD memory card reader (O2 Micro SD/MMC)
  - Keyboard
  - Touchpad
  - Audio (Realtek ALC3226 equivalent to ALC292) internal speakers
  - LCD brightness 
  - Volume buttons
  - Fn keys (with the exceptions of brighness keys)
  - Sleep
  
## Not working
  - VGA
  - Internal microphone
  - Audio jack
  - Fn brighness keys
  - Deep sleep
  
## Tested on
  - [Dell Latitude E5440](https://www.dell.com/support/manuals/en-us/latitude-e5440-laptop/delllatitudee5440_om-v2/specifications?guid=guid-fa08d88f-67d7-4277-a7b9-d872f106a82b&lang=en-us)
  - Intel(R) Core(TM) i5-4300U CPU @ 1.90GHz
  - RAM 8 GB
  - 14" LCD HD+ (1600 x 900)
  - Samsung SSD PM851 mSATA 128GB

## Installation guide

Installing macOS on Dell Latitude E5440 will be very relaxing because the hard job to prepare the EFI partition has been already completed.
The only effort requested to you is to prepare the macOS installation USB key.

https://dortania.github.io/OpenCore-Install-Guide/installer-guide/#creating-the-usb

I suggest to use directly my EFI partition also on USB key.

## Detailed instructions

https://dortania.github.io/OpenCore-Install-Guide/

