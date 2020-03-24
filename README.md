# Install SteamOS in target PC

1. Download the SteamOS installation from [here](https://store.steampowered.com/steamos/download/?ver=custom)
1. Unzip the SteamOS.zip file to a blank, FAT32-formatted USB stick. Make sure to use an MBR partition.
1.Put the USB stick in your target machine. Boot your machine and tell the BIOS to boot off the stick. (usually something like F8, F11, or F12 will bring up the BIOS boot menu).
1. Make sure you select the UEFI entry, it may look something like "UEFI: Patriot Memory PMAP". If there is no UEFI entry, you may need to enable UEFI support in your BIOS setup.
1. Selected "Expert install" from the menu.
1. Selected your preferred language, location, and keyboard layout.
1. You will have the option to change the default disk partitioning.
1. The rest of the installation is unattended and will install SteamOS.
1. After installation is complete, the system will reboot and automatically log on and install Steam. At this point an internet connection is required. If you have an internet connection, Steam will automatically install itself. If you do not have an internet connection (for instance, if you need to connect to a WiFi access point) you will get a popup telling you this. Close the popup and you will get the network configuration UI where you can set up your network. Once you are connected to the internet, close this UI and Steam will install itself.
1. After Steam finishes installing, your system will automatically reboot and create a backup of the system partition.
1. When the backup completes, select "reboot" to boot into your freshly installed SteamOS
