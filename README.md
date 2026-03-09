# Annapurna-Labs-Alpine-MikroTik-RouterBOARD-1100AHx4
OpenWrt - Annapurna Labs Alpine MikroTik RouterBOARD 1100AHx4

I have started working on adding support for the Annapurna Labs Alpine platform to OpenWrt in order to run OpenWrt on the MikroTik RB1100AHx4 router.

The RB1100AHx4 is based on the AL21400 SoC (Annapurna Labs Alpine, ARM Cortex-A15). The goal of this work is to enable a clean and maintainable OpenWrt port for this device.

Current work includes:

- Adding Alpine platform support to OpenWrt
- Integrating the Alpine Ethernet MAC driver
- Implementing MDIO GPIO support for switch communication
- Creating the required Device Tree definitions for the RB1100AHx4
- Preparing support for the RTL8367 switch

This effort is still a work in progress, but the objective is to get the device to boot OpenWrt and gradually bring up all hardware components.

Contributions, technical feedback, and testing are welcome.


<img width="861" height="308" alt="image" src="https://github.com/user-attachments/assets/630133d6-fdd9-47ce-a371-a5fa0039b015" />

