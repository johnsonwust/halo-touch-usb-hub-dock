# Firmware And Resource Package

This folder contains firmware binaries, TF card resource files, AIDA64 configuration, and a STEP model prepared for GitHub distribution.

## Main Product

`HALO_TOUCH_USB_HUB_DOCK` is the package for HALO TOUCH USB Hub Dock with Clock V2.

Important paths:

- `HALO_TOUCH_USB_HUB_DOCK/firmware`: bootloader, partition table, and firmware binaries.
- `HALO_TOUCH_USB_HUB_DOCK/TFCARD`: files to copy to the device TF card.
- `HALO_TOUCH_USB_HUB_DOCK/TFCARD/txt/user_guide.txt`: English quick user guide for the device text reader.
- `PRODUCTION_FLASHING`: current factory production flashing tool and firmware package.

## Other Packages

- `OLD_DEVICES`: God Eye, Taiji Pi, iCRT secondary display, Fuxuan Necklace, 86 Box, and other older-device firmware/resources.
- `GUM_DAC_USB_Dongle`: GUM DAC USB dongle resources.
- `TAIJI_STRESS_RELIEF_KNOB`: Taiji stress relief knob firmware and TF card resources.
- `TAIJI_PI_LITE`: Taiji Pi Lite firmware and TF card resources.
- `TAIJI_VIEW_PI`: Taiji View Pi firmware and TF card resources.

## Shared Files

- `AIDA64 Extreme.zip`: AIDA64 installer/archive supplied with the package.
- `my_aida64_setting.rslcd`: AIDA64 Remote Sensor LCD layout file.
- `solid_base.step`: 3D STEP model for the solid base.

## TF Card Notes

Do not delete required runtime directories from the TF card. If the TF card is replaced, format the new card as FAT32 and copy the corresponding `TFCARD` directory contents to the card root.

Common directories:

- `fonts`: font files.
- `mjpeg`: MJPEG animations.
- `music`: audio files.
- `night7`: runtime assets, boot animation, and alarm audio.
- `pic`: JPG images.
- `aida64`: AIDA64 display backgrounds.
- `txt`: text reader files.
- `weather`: weather animations.
- `clockbg`: clock backgrounds.

## References

- Product page: https://www.tindie.com/products/johnson/halo-touch-usb-hub-dock-with-clock-v2/
- Bluetooth knob / Taiji View Pi Chinese guide: https://pressf5.run/?p=227
- Old devices Chinese guide: https://pressf5.run/?p=119
