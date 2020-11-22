# Privacy A-GPS Module
This module provides improved privacy on A-GPS functionality.

## How it works?
   The stock Android **_gps.conf_** file found in `system/vendor/etc/gps.conf` is replaced with a new one edited for better privacy.  
   The default file found in most ROMs uses Google assisted A-GPS server which leaks your [IMSI](https://blog.wirelessmoves.com/2014/08/supl-reveals-my-identity-and-location-to-google.html)
   
## Requirements
- A device with Qualcomm Snapdragon chipset.
- Android Oreo+.
- Rooted with Magisk and Magisk Manager installed.

## Instructions
__It's Magisk install-able, don't install it with TWRP!__

1. Go to Magisk Manager **_Modules_** section.
2. Click on **_Install from storage_** button and search/find for **_"magisk-privacygps.zip"_** file and click on it.
3. After installation, reboot your device.
4. Done.




