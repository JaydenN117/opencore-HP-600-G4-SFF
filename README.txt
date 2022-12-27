HP 600 G4 SFF
EFI intended to be used for macOS 12, I believe it would work for macOS 11->13, however it was tested on 12.
I followed Dortania guide which made the process fairly straightforward.


Also,thanks to u/aleelmaitro on Reddit for information on getting RX550 lexa working
https://www.reddit.com/r/hackintosh/comments/tdz65y/rx_550_lexa/

Note: Will need to fill in info from GenSMBIOS prior to booting this.

My specifications
intel i7-8700 processor (should work on 8th gen i3,i5,i7)
Dell AMD RX550 4gb (device ID: 699F)
SATA SSD (Can do M.2 need NVMEFix kext)
ASUS BT400 bluetooth module
No wifi card (can be added with relevant kext)

Versions:

Opencore       0.8.3

Kexts
AppleALC       1.7.4
WhateverGreen  1.6.2
Lilu           1.6.2
VirtualSMC     1.3.0
IntelMausi     1.0.7
BlueToolFixup  2.6.3 (for BT400 to work)
USBToolBox     1.1.1
UTBMap

Problems
RTC post error on every boot
Graphical bugs when using hardware acceleration on some apps

If anyone has any suggestions on how to fix I would appreciate them!
