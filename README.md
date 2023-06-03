# ThunderboltReset
Reset and disable Thunderbolt ICM 

#

Thunderbolt Reset

This plugin will disable the ICM in the Alpine Ridge in order for OSX to take over as the LC.

Please note that due to the fact that the AR was designed by Intel, the controller becomes very unstable if the ICM was powered up enabled and then subsequently disabled (by this plugin). Therefore, this should only be used for testing.

Lilu is required for this to work.
Guides
#
[Patching Ridge NVM](https://github.com/osy/ThunderboltReset/blob/master/PatchingNVM.md)
[Patching Ridge NVM](https://github.com/osy/ThunderboltReset/blob/master/PatchingACPI.md)
#

Build Requires Lilu and MacKernelSDK

#
CREDITS TO
[osy](https://github.com/osy/ThunderboltReset)
