# WIIXPLORER Channel Forwader
#WiiXplorer Forwarder Channel v12#

#Features:
Channel name: WiiXplorer
Channel ID: WIIX
Wii settings: working (language, screen size)
Multilangual channel name and splashscreen in fonction of Wii Language Setting
(English, Japanese, French, Dutsh, German, Italian, Spanish)


#Credits:
Dimok: forwarder sources updates and executable
Base wad: by Leathl/Jeanny ( Animated Forwarder Channels - Sammelthread ) Modified by Neorame
dj_skual: multilangual, splashscreens

#Linking way:
try to boot .dol, then .elf in the following paths:
- your update path if exist in WiiXplorer.cfg file (sd(or usb):/config/WiiXplorer/WiiXplorer.cfg).
- sd:/apps/WiiExplorer/
- usb:/apps/WiiExplorer/
- sd:/apps/WiiXplorer/
- usb:/apps/WiiXplorer/
- return to WiiMenu if nothing found

#WARNING:
This file need to be instaled on your Wii, using a wad manager.
Be carefull, it's better to have a restor tool like BootMii (and a dumped NAND) before install this one.
The WiiXplorer Team can't be responsible for any damage on your Wii!!!
USE AT YOUR ON RISK!!!

#ChangeLog:
v1
 - First public Release.

v2
 - Updated to new libogc,
 - USB Loading fixed.

v3
 -fix for new wiixplorer load.

v4
 -Changed to the way WiiXplorer boots dols/elfs
 -Updated png/pngu on the source
 -Disabled USB shutdown on exit (Slow HDD wakeups should have more time now)

v5
 -Changed the channel to a new one by Neorame
 -Changed dol with new change in revision 4.1 of forwarder
 -Added new splashscreen matching with the new channel

v6
 -USB2.0 support added
 -Changed image rescale from 16:9 to be done internally by GX. Using less space now.
 -Fix for some usb drives.

v7
 -USB2.0 support with IOS58
 -Proper USB shutdown on exit

v8
 -AHBPROT enabled
 -Default channel IOS changed to IOS58
 -Added NTFS support
 -Added mount of all primary FAT/NTFS partitions on USB

v9
 -Fixed garbage on screen / greenscreen right before application boot

v10
 -Added a loop to wait for slow starting up USB devices (thanks gsouders)

v11
 -Ignore MBR entry for partitions and check the boot record sector instead

v12
 -Support for drives with sector size > 512 bytes
 -Fix bug with endless wait for USB initialization -> now 10 secs
 -compiled with new libogc for better USB compatibility and new filesystem libs
