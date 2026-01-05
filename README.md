## Creality CR-M4 printer.cfg for Debian Sonicpad + Trianglelab CHCB-OT Hotend + Zuff modular cooling system

### dependencies (similar settings might work)
- Jpe230's version of Sonic Pad Debian (https://github.com/Jpe230/SonicPad-Debian)
- Triangle Lab CHCB-OT Hotend (https://ja.aliexpress.com/item/1005007101060249.html?spm=a2g0o.order_list.order_list_main.5.39cb1802mMTZcZ&gatewayAdapt=glo2jpn)
- efficient cooling system like Zuff's MODULR cooling system (https://cults3d.com/en/3d-model/tool/modulr-duct-5015-fan-ender-3-s1-s1-pro-sprite-extruder-accelerometer-led-strip)
NOTE: CHECK your thermistor connector on extruder board before buying CHCB-OT *

### summary
This is slightly modified version from original CR-M4's cfg file for Sonic Pad. I had to modify some pin output, including accelrometer, BLtouch.
I have edited the extruder max_power to 0.5 to prevent dropping power error. You should adjust it if you are using stock / different hotend, but it makes print a lot better.

with this settings, I have no underextrusion!
works fine till now, probably works with another variants.

### Orcaslicer setting
I also share Orcaslicer setting. It makes way smoother than stock setting, and no too much accellaration, less underextrusion and less support sticking on the model!
Tips:
- Drop speeds, enable overhang
- enable NORMAL Zhop
- Edit line width, retracction and so on

I printed with wet eSUN Pla+(left: mostly stock setting, right: current setting)
I think I can do better, so I'd do some more adjustments.
![IMG_4145](https://github.com/user-attachments/assets/70c47f56-1eac-4104-a354-6f9d06c75465)
