# PROJECT DEAD!
## because WireGuard is now officially supported as of EdgeOS 3.0.0: https://community.ui.com/releases/EdgeRouter-3-0-0/33ee3852-b5db-453e-ad14-430bc218c02f

# ER-wizard-WireGuard
WireGuard Wizard for Ubiquiti EdgeMAX Devices supporting Wizards

## Credits
- Uses [WireGuard for Ubiquiti](https://github.com/WireGuard/wireguard-vyatta-ubnt) package
- Uses [wireguard.js](https://git.zx2c4.com/wireguard-tools/tree/contrib/keygen-html/wireguard.js) javascript library to generate wireguard keys
- Uses [QRCode.js](https://github.com/davidshimjs/qrcodejs/) javascript library to generate QRcode

## Features
- Display status of WireGuard package installation
- Display status of running instances/processes
- Display status of Wizard version
- Setup script to install and configure WireGuard (with previous wg0 settings) after a firmware upgrade
- Option to manually upgrade if auto-upgrade is disabled
- Automatic upgrade with daily check for latest release of "ER-wizard-WireGuard" and "WireGuard for Ubiquiti"
- Generates private key automatically
- Displays public key in wizard with option to show it as QRcode
- Easy configuration of wg0 interface (does not modify but *save on upgrade* any existing wg1-wg999 interfaces)
- Display latest handshake for each configured peer
- Generate configuration for peers and display it as QRcode (config also shown in browser console for copy&paste)

## Installation
To install the wizard in EdgeOS:
- [1] Click on the "Wizards" tab
- [2] Click the "+" next to Feature Wizards
- [3a] Enter a name for the wizard, for example "WireGuard"
- [3b] Upload latest ER-wizard-WireGuard.tar file from [releases](https://github.com/vchrizz/ER-wizard-WireGuard/releases/latest) in this repository
- [3c] Click "Save"
- [4] Click the wizard

![Screenshot of ER-wizard-WireGuard Installation](https://github.com/vchrizz/ER-wizard-WireGuard/blob/main/ER-wizard-WireGuard-installation.png)

## Screenshot of running wizard
![Screenshot of ER-wizard-WireGuard](https://github.com/vchrizz/ER-wizard-WireGuard/blob/main/ER-wizard-WireGuard-screenshot.png)
