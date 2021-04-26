# HP-Pro-3500-MT-Hackintosh

**High Sierra for the HP Pro 3500 MT, i5 3470 (3rd gen.) and Nvidia GTX 1050ti. I am unable to test newer versions without an AMD GPU.**

**This isn't a tutorial, but rather the files I used on my machine. Consult the r/Hackintosh subbreddit for further help.**

# Installation:

Boot arguments during installation:
``-v debug=0x100 nv_disable=1 kext-dev-mode=1 dart=0``

# Post Installation:

Use Clover Configurator to generate a new serial number, board serial number and SmUUID after installation.

Install all macOS updates and install the latest Nvidia driver, then remove `nv_disable=1` from the boot args.
