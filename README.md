# LEDE-MR33
Bringup for the Cisco Meraki MR33 Access Point on LEDE!

Currently based on commit [fa3649d97ef08b375e628a4875e67f91c6d87644](https://github.com/lede-project/source/commit/fa3649d97ef08b375e628a4875e67f91c6d87644)

Building
-----
#### Build Only
`./build.sh`

#### Modify Configs and Build
`./build.sh modify`

Note that you will need to run a modify on the first compile to select the ipq806x target, MR33 device in the LEDE menuconfig.

Booting
-----
It's a [secret](https://www.youtube.com/watch?v=sTSA_sWGM44).

Flashing
-----
This is also a [secret](https://www.youtube.com/watch?v=gvYfRiJQIX8).

To Do
-----
##### MR33
* Wireless (SoC Radios)
* PCIe Wireless (If Possible)
* NAND Support
* Bluetooth
* Fixup Ethernet Driver (very hacky currently)
* System Integration
* Sysupgrade Support
* Cleanup DTS if possible

Working
-----
##### MR33
* Ethernet (dirty code)
* LED's/GPIOs
* Reset button
* Kernel Device Profile

Notice
------
No promises this won't brick your unit, and no promises that this will even work!
