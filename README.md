# Hackintosh-OpenCore-HP-9470m-1600x900-Big-Sur-Broadcom-Wifi
OpenCore EFI bootloader for HP 9470m with 1600x900 resolution and Broadcom Wi-Fi

<p align="center">
  <img width="400" height="300" src="/img/HP_9470m.png">
</p>

# Specifications:
* CPU: Intel Core i5-3437U
* GPU: Intel HD Graphics 4000
* Resolution: 1600x900
* Audio: IDT 92HD91BXX
* Wi-Fi: BCM94352HMB
* Bluetooth: Broadcom Bluetooth 4.0
* Ethernet: Intel 82579LM
* Touchpad: Synaptics SMBus TouchPad
* Card reader:
  - JMicron Card Reader
  - Alcor Micro USB Smart Card Reader
* Fingerprint: Synaptics Fingerprint Sensors

# Version: 
* OpenCore: 0.7.1
* macOS: 10.16 (Big Sur)

# BIOS settings:
* Boot mode: UEFI Native (without CSM)
* SATA mode: AHCI

# Working:
- [x] Intel HD Graphics 4000
- [x] Sleep
- [x] Audio (using AppleALC.kext with layout-id = 13)
- [x] Internal microphone
- [x] External microphone
- [x] Touchpad (with multi gestures)
- [x] Battery indicator
- [x] Ethernet
- [x] Wi-Fi
- [x] Bluetooth
- [x] CPU power management
- [x] Webcam
- [x] USB ports
- [x] Fn function keys
- [ ] Card reader
- [ ] Synaptics Fingerprint Sensors

# Not test:
* Mini Displayport external port
* D-Sub external port

# SMBIOS:
iMac16,1
 
# Note:
Don't use this EFI bootloader for 1366x768 resolution

# Screenshots:
<p align="center" style="margin:20px">
  <img align="center" src="/img/BigSur_Control_Center.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/BigSur_Information.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/BigSur_Settings.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/BigSur_Trackpad.png">
</p>
