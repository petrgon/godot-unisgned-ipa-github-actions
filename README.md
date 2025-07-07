# Godot iOS Build (Unsigned IPA) – GitHub Action Script

This repository provides a ready-to-use GitHub Action script for building a Godot project for iOS. It enables you to create an iOS build without requiring access to a Mac.

Special thanks to [mak448a](https://github.com/mak448a) for their work, which served as the foundation for this script. See their [repository](https://github.com/mak448a/build-ios) for reference. 

> [!WARNING]
> Some one-time configuration is required. Please refer to the comments within each step of the YAML file for setup instructions.

> [!WARNING]
> The output of this pipeline is not intended for distribution. It is meant for local development only. To run the unsigned IPA on your device, you will need to use sideloading methods.

## How to Sideload an Unsigned IPA

There are several methods to sideload an unsigned IPA onto your iOS device. Most of them typically involve the following steps:
1. Have an Apple ID and iTunes installed on your PC or Mac to retrieve your device’s UDID.
1. Install a sideloading server on your PC or Mac and connect it with your Apple account.
1. Download a third-party app store and mark it as trusted.
1. Install the IPA file using the third-party app store.
1. Enable Developer Mode on your iOS device.
1. Add your Apple account as a trusted developer on your iOS device.

> [!WARNING]
> The sideloaded app will remain available on your device for 7 days. After that period, you will need to renew its authorization using the sideloading server.

For a step-by-step guide, I recommend referring to the instructions provided by the VCMI project: 👉 [VCMI iOS Installation Guide](https://vcmi.eu/players/Installation_iOS/)
