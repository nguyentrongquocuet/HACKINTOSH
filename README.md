# HACKINTOSH
# DELL VOSTRO 3568
* SPECS:
 - Atheros wifi card
 - Intel bluetooth card
 - RT8111 LAN card
 - i5 7200U Kabylake
 - Samsung 860 Evo SSD
 - 8GB of 2400Mhz duo channel ram
 - 1366*768 + 1920*1080 display monitor
 - Synapstic touchpad
* Desired OS: Macos Catalina
 
# If Windows's EFI get removed
  * use these via ventoy [OS_RESCUE](https://onedrive.live.com/?id=814D2F5978F4306A%212184&cid=814D2F5978F4306A)
# Wanna boot to macos without usb stick?
  * Go to Macos, use (MountEFI)[https://github.com/corpnewt/MountEFI] to mount the efi partition, then add new partition, name it EFI, copy the efi folder to the new partition. That's it
# Want mouse and touch pad scroll direction to be like on window/linux?
  * Use (UnnaturalScrollWheels)[https://github.com/ther0n/UnnaturalScrollWheels]
# Fix jackphone issue:
  * (Read this)[https://elitemacx86.com/threads/audio-distortion-when-using-headphones-on-laptops-clover-opencore.185/]
  * Download (CodecCommander)[https://bitbucket.org/RehabMan/os-x-eapd-codec-commander/downloads/], extract and copy hda-verb to /usr/bin
  * If you get `Operation not permitted` disable SIP
  * After disabled SIP, if `Readonly...` is threw, type `sudo mount -uw /`
  * Add Jack fix to Applications, then add to Startup items

# Known issues
* Headphone micro not work
