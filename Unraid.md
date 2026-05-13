# Unraid Installation

## Requirements

Server (Old PC or Mac) 

Keyboard and Monitor *(for initial configuration only)*

USB Flash drive 4-32GB

Ethernet connection to LAN

## Step 1 - Unraid USB and Installation 

Download Unraid USB Creator from [here](https://unraid.net/download)

Install Unraid to USB drive

Remove USB drive and plug it into your server

Boot into your server's BIOS settings and make the following changes:

- Configure the system to boot from the USB flash device

- Enable hardware virtualization-specific features (including IOMMU), if applicable

- You can find more details on BIOS configuration in the [Advanced BIOS configuration guide](https://docs.unraid.net/go/advanced-bios-config/)

- Save your BIOS configuration changes and exit to boot Unraid OS

Boot Unraid (Select Unraid OS not GUI)

Once installed it will show IPv4 address

Using another computer type this address into your browser to go to the Web GUI

Setup a strong password for root user

Activate Unraid or select Trial

Unraid is now installed and runs from USB drive, be sure not to unplug USB drive while server is running

## Step 2 - Assign devices to the Array and Pool

Now you’re ready to assign devices for Unraid to manage.

- Assign devices in the “Main” tab of the Unraid WebGUI. On this page, you’ll see a list of Array device and Pool device assignments, as well as any unassigned devices and the boot device.
- Use the dropdowns to select disks for your array (parity and non-parity drives) and pool devices. [Learn more about storage management.](https://docs.unraid.net/go/quick-install-guide-assigning-devices/)
- Once you have assigned all your devices, select the “Start” button under “Array Operation.” This will mount your devices and start the array.
- Once you have started the array, plan and create shares to simplify how you store data across multiple disks. [Learn more about shares.](https://docs.unraid.net/go/shares/)

For more details and recommendations for assigning disks, see our product documentation.
