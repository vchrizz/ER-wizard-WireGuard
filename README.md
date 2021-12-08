# ER-wizard-WireGuard
WireGuard Wizard for Ubiquiti EdgeMAX Devices supporting Wizards

Uses [WireGuard for Ubiquiti](https://github.com/WireGuard/wireguard-vyatta-ubnt) package

## Features
- Display status of WireGuard package installation
- Display status of running instances/processes
- Display status of Wizard version
- Setup script to install and configure WireGuard after a firmware upgrade
- Option to manual upgrade if auto-upgrade is disabled
- Automatic upgrade with daily check for latest release of "ER-wizard-WireGuard" and "WireGuard for Ubiquiti"
- Easy configuration of wg0 interface (does not modify any existing wg1-wg999 interfaces)

## Installation
To install the wizard in EdgeOS:
- [1] Click on the "Wizards" tab
- [2] Click the "+" next to Feature Wizards
- [3] Enter a name for the wizard, for example "WireGuard"
- [3] Upload the ER-wizard-WireGuard.tar file from [releases](https://github.com/vchrizz/ER-wizard-WireGuard/releases) in this repository
- [4] Click the wizard

![Screenshot of ER-wizard-WireGuard Installation](https://github.com/vchrizz/ER-wizard-WireGuard/blob/main/ER-wizard-WireGuard-installation.png)

## Screenshot of running wizard
![Screenshot of ER-wizard-WireGuard](https://github.com/vchrizz/ER-wizard-WireGuard/blob/main/ER-wizard-WireGuard-screenshot.png)