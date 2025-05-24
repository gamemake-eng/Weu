---
title: "Weu"
author: "Mo S"
description: "A dual screen Microconsole powered by the CM4"
created_at: "2025-05-22"
---

# First Entry (May 22 2025)

All I did today was make a KICAD project and added a power source to the console schematic. The CM4 doesn't require any external circutry for power so I just connected it directly to a usb-c power line set to pull 5v.

**Total Time: 1 min**

# Making some more progress (May 23 2025)

Today I wanted to make a bit more progress on the console schematic. After some thinking I decided to add a usb debug port that would be used for flashing the EMMC. But turns out adding a USB-OTG port was a little more compilcated when you also want to have a USB hub Ic. So I decided to add a SD card connector and just use a CM4 lite instead since that would have been easier to flash anyway. I'm going to go though this slowly right now before the summer so tomorrow I will add some usb ports and also some microcontrollers for communicating with the controller.

**Total time: 1 hr (including research)**
