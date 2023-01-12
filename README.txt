HP 600 G4 SFF INTEGRATED GRAPHICS VERSION
EFI tested on macOS 12,13, I believe it would also work on 11.
I followed Dortania guide which made the process fairly straightforward.


Note: Will need to fill in info from GenSMBIOS prior to booting this.

My specifications
intel i7-8700 processor (should work on 8th gen i3,i5,i7)
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
Still need to test this exact configuration, but previously had issues with only one monitor working.
RTC error
