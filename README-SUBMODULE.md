# libdivecomputer Git Submodule

This directory contains [libdivecomputer](https://www.libdivecomputer.org/) as a Git submodule.

## About libdivecomputer

libdivecomputer is a cross-platform, open-source library for communication with dive computers from various manufacturers.

**Features**:
- Support for 100+ dive computer models
- Multiple transport types (USB, Serial, Bluetooth, BLE)
- Comprehensive data parsing
- Active maintenance by Subsurface team

## Updating

To update to the latest version:

```bash
cd packages/libdivecomputer
git pull origin master
cd ../..
git add packages/libdivecomputer
git commit -m "Update libdivecomputer"
```

## Building

See platform-specific build scripts:
- iOS: `../../dive-computer-capacitor/ios/scripts/build-libdc.sh`
- Android: `../../dive-computer-capacitor/android/scripts/build-libdc.sh`

## License

libdivecomputer is licensed under LGPL v2.1. See their LICENSE file for details.
