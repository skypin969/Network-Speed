# Network Speed

A KernelSU Next module that locks the network mode to NR/LTE (LTE, LTE_CA, NR) as soon as the phone finishes booting.

## What it does
- Keeps the allowed network types at LTE, LTE_CA, and NR after every reboot.
- If the allowed types change, the module restores NR/LTE for about 2 minutes after boot.

## Requirements
- **KernelSU Next** (root) is required. This module will not work without it.

## Installation
1. Download `Network.Speed.zip` from the **Releases** page.
2. Open KernelSU Next, go to **Modules**, choose **Install from storage**, and select the zip.
3. Reboot the phone.
4. Check the network mode in settings. It should be set to NR/LTE right away.

## Uninstallation
Open KernelSU Next, select the **Network Speed** module, and remove it. Reboot afterward.

## Notes
- The module uses `cmd phone set-allowed-network-types-for-users`. Behavior may differ on other ROMs.
- The module does not modify the modem or any partition.

## Developer
Skypin 969, Telegram @Skypin969
