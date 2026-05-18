# Unraid Installation

## Requirements

Server (Old PC or Mac) 

Keyboard and Monitor *(for initial configuration only)*

USB Flash Drive 4-32GB *(name branded)*

Ethernet Connection to LAN

## Step 1 - Unraid USB and Installation 

Download Unraid USB Creator from [here](https://unraid.net/download)

Install Unraid to USB Drive

Remove USB Drive and plug it into your server

Boot into your server's BIOS settings and make the following changes:

- Configure the system to boot from the USB flash device

- Enable hardware virtualization-specific features (including IOMMU), if applicable

- More details on BIOS configuration in the [Advanced BIOS configuration guide](https://docs.unraid.net/go/advanced-bios-config/)

- Save your BIOS configuration changes and exit to boot Unraid OS

Boot Unraid *(Select Unraid OS not GUI)*

Once installed it will show local IPv4 address

Using another computer *(on the same network)* type this IP address into your browser to go to the Unraid Web GUI

Setup a strong password for root user

Activate Unraid or select Trial

Unraid is now installed and runs from USB drive, be sure not to unplug USB drive while server is running

## Step 1.5 Dark Mode

Settings > Display Settings > Dynamix color theme - Black

Header custom text color - fd882f

Header custom background color - 1c1b1b

## Step 2 - Assign devices to the Array and Pool

Assign array devices from "Main" Tab

Select disks for your array (parity and non-parity drives) and pool devices / cache (can be a USB Drive)

Select the “Start” button under “Array Operation”

This will mount your devices and start the array

Go to Settings Tab > Disk Settings > Enable Auto Start - Yes

Main Tab > Array Operation > Format

*After Format complete, Unraid will mount Disks*

