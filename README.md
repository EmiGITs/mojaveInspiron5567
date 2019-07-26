# mojaveInspiron5567
MacOs 10.14.4 Mojave-Dell Inspiron 15-5000 5567 Config

What is Working:

- Trackpad with gestures (Some not working, using Three Finger gestures)
- Keyboard Backlight
- HDMI
- External Audio
- Integrated GPU
- Internal Audio
- Internal Microphone
- Camera

- Native Power Management
- Battery Status
- All 3 Usb's
- Wireless (For now, using USB bundle Nisuta NS-WIU600N2)
- Ethernet
- AppStore


What is not working

- Dedicated GPU
- Integrated Wireless Card (And never will, needs to be replaced)
- Bluetooth (Haven't tried it yet but doubt it work)
- Card Reader (Same as bluetooth, never tried it but probably doesn't work)


MacOs version installed: Installed via Usb using 10.14.4 vanilla

Bootloader: Clover 4979

ACPI: Generated and patched DSDT+SSDT

Audio Layout-ID: ALC256 with Layout-ID 13 (As a custom propierty on config.plist)

To do:

- Delete unnecessary configurations on config.plist
- Update Kexts
- Update Clover
- Update 10.14.4 to 10.14.6
