# DTS Sound Infinix ZERO ULTRA Magisk Module

## DISCLAIMER
- DTS app and blobs are owned by DTS™.
- The MIT license specified here is for the Magisk Module only, not for DTS app and blobs.

## Descriptions
- Equalizer sound effect ported from Infinix ZERO ULTRA (Infinix-X6820) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Post process type sound effect
- Changes/spoofs ro.build.product to x6820_h773 and ro.product.model to Infinix X6820 which may break some system apps and features functionality

## Sources
- https://dumps.tadiphone.dev/dumps/Infinix/infinix-x6820 sys_tssi_64_armv82_infinix-user-13-TP1A.220624.014-396124-release-keys
- libsqlite.so: https://dumps.tadiphone.dev/dumps/zte/p855a01 msmnile-user-11-RKQ1.201221.002-20211215.223102-release-keys
- libmagiskpolicy.so: Kitsune Mask R6687BB53

## Screenshots
- https://t.me/ryukimodsscreenshots/34

## Changelog

v0.7
- Does not disable raw playback (You can use Audio Compatibility Patch Reborn Magisk Module instead)

v0.6
- Fix wrong target in latest KernelSU

v0.5-R
- Fix wrong file permissions in some ROMs

v0.5
-Tidy up aml.sh
- Exclude audioeffectshaptic.xml
- Abort installation if fail to mount mirror system

v0.4
- Improve /odm and /my_product support detection

v0.3
- Fix script bug at installation for libsqlite.so detections

v0.2
- Forgot to add libmagiskpolicy.so
- Add Action button to clear apps caches
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.1
- Initial release

## Requirements
- arm64-v8a or armeabi-v7a architecture
- Android 8.0 (SDK 26) and up
- HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- Install this module http://ddl.to/d/7fSRO via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/androidryukimodsdiscussions/29836 only if using any other else audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards

## Optionals
- https://t.me/ryukinotes/65
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
- https://t.me/ryukinotes/65
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Known Issues
- Boost Bass, Treble, & Vocal doesn't work in headset nor Bluetooth Audio
- Probably still bug microphone in game apps in some devices

## Credits and Contributors
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/ryukinotes/25


