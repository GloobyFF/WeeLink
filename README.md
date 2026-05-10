# Vlink

Vlink is a Windows launcher for native PCVR streaming to Apple Vision Pro.

## Download

Download the latest Windows installer from the GitHub Releases page:

- `VlinkSetup-0.5.0.exe`

## Requirements

- Windows 11
- NVIDIA GPU
- SteamVR / OpenXR-compatible PCVR content
- Apple Vision Pro client on the same local network

## Important Licensing Notice

This installer includes NVIDIA CloudXR components. Before publishing this file
publicly, confirm that your NVIDIA CloudXR license allows redistribution of the
included binaries.

If redistribution is not allowed, publish a Vlink-only installer instead and
ask users to install NVIDIA CloudXR Runtime separately.

## Install

1. Download `VlinkSetup-0.5.0.exe`.
2. Run the installer on the Windows PC that will host PCVR streaming.
3. Start Vlink.
4. Launch the Vision Pro client on the same network and pair with the PIN shown
   in Vlink.

## Security

Windows may show an "Unknown Publisher" or SmartScreen warning if the installer
is not code-signed. For public releases, code signing is recommended.

