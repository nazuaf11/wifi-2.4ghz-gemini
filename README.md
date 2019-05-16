# Magisk Force 2.4GHz band WifI

Prefer (Force) Using 2.4Ghz Band WiFi (gemini)


## Details

By default, Mi5 system provided ini file for controlling WiFi behaviour.  This module will modify `WCNSS_qcom_cfg.ini` in order to change prefer WiFi band to only 2.4GHz. This will force PdaNet to use 2.4Ghz band WiFi for WiFi Direct Hotspot. This will be useful for laptop with no 5Ghz WiFi band support.


Prefer using 2.4Ghz for WiFi
```
BandCapability=1
```
This module has only been tested using Mi5 Gemini. 



## Instructions
1. Install this module.
2. Enjoy!

## NOTICE

* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.
* Recent fixes:
New installation logic by finding target file with GNU find.

## Credit & Support

* Copyright (C) 2019 nazuaf11 <pojefauzan@yahoo.com>
* Any issue or pull request is welcomed.
* Star this module at [GitHub]
