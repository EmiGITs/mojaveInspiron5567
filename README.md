# mojaveInspiron5567
**MacOs 10.14.6 Mojave-Dell Inspiron 15-5000 5567-1753 Config**

**_This repo is no longer maintained, it can be used as an start for a better MacOs 10.14.6 installation. Keep in mind that Clover should be updated and bugs listed bellow will be present (And probably some more i haven't noticed). Good Luck._**




## Currently Working:

- Trackpad with gestures (Some not working, using Three Finger gestures)
- Keyboard Backlight
- HDMI
- External Audio
- Integrated GPU
- Internal Audio
- Internal Microphone
- Camera
- Headphones Jack
- Native Power Management
- Battery Status
- All 3 Usb's
- Wireless (For now, using USB bundle Nisuta NS-WIU600N2)
- Ethernet
- AppStore


## Currently not working

- Dedicated GPU
- Integrated Wireless Card (And never will, needs to be replaced)
- Bluetooth (Haven't tried it yet but doubt it work)
- Card Reader (Same as bluetooth, never tried it but probably doesn't work)

## Known bugs/glitches

- After Sleep already connected headphones needs to be unplugged and plugged again (Does not always happen)
- After Sleep microphone will stop working
- After Sleep audio will be distorted unless a restart is made (IMPORTANT)
- Function keys not working properly, some function keys like f5 won't do anything, used Karabiner to re-map but can't get to work some keys
- ~~Bootcamp or Unetbootin can't recognize any Usb.~~ balenaEtcher seems to work


MacOs version installed: Installed via Usb using 10.14.4 vanilla, updated to 10.14.6 after a few weeks

I don't suggest using neither Clover folder or Kexts directly, use them as a reference and set your configuration up following existent guides. In any case if you want to boot from usb and install then you need to move Library Extension kexts to your USB/Clover/Kexts/Other.

# Bootloader: 
- ~~Clover 4979~~ Updated on Commit 124a8b5
- Clover 5018

Due to testing purposes i'm using debug versión of VoodooPs2Controller


SMBIOS: MacBook Pro 11,1

ACPI: Generated and patched DSDT+SSDT

Audio Layout-ID: ALC256 with Layout-ID 13 (As a custom propierty on config.plist)

## To do:

- Fix Audio-Microphone glitch
- Fix inversed function keys and get all F1-F12 keys to work (Probably related to VoodooPs2Controller)
- Fix Unetbootin-Bootcamp usb recognition
- Delete unnecessary configurations on config.plist
- ~~Update Clover~~ Done in Commit 124a8b5 to Clover 5018
- ~~Update 10.14.4 to 10.14.6~~ Done in Commit 124a8b5

## Credits

Thanks to the clover team and people at tonymacx86

[Clover](https://github.com/CloverHackyColor/CloverBootloader)

[tonymacx86](https://www.tonymacx86.com/)
