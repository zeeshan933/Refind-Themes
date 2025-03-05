# Wave Theme for rEFInd Bootloader

## Overview
The **Wave Theme** is a custom theme for the rEFInd bootloader, designed to provide a modern and visually appealing boot experience.

## Installation

1. Clone or copy the `wave` theme directory to your rEFInd themes directory:
   ```sh
   sudo mkdir -p /boot/efi/EFI/refind/themes
   sudo cp -r themes/wave /boot/efi/EFI/refind/themes/
   
## Edit refind.conf
Modify your refind.conf file to use the Wave theme:

sudo nano /boot/efi/EFI/refind/refind.conf

## Enable the Wave theme
include themes/wave/theme.conf

