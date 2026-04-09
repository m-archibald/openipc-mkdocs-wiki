# Installation Guide

OpenIPC firmware can be installed on IP cameras using various methods depending on the camera model and manufacturer.

## Installation Methods

### 1. Coupler Method
The [Coupler](https://github.com/openipc/coupler/) project makes available firmware images which can be installed using the firmware upgrade mechanisms which are built into the factory firmware of many cameras.

### 2. UART/TFTP Method
Flashing the OpenIPC firmware using the [*U Boot* bootloader](https://en.wikipedia.org/wiki/Das_U-Boot) which is included in the vendor firmware. This method requires opening the camera case and connecting a UART adapter.

## Choose Your Platform

Select your camera's System on Chip (SoC) for specific installation instructions:

- [Goke Installation](goke.md) - Goke GK72xx series
- [HiSilicon Installation](hisilicon.md) - HiSilicon Hi35xx series  
- [Novatek Installation](novatek.md) - Novatek series
- [SigmaStar Installation](sigmastar.md) - SigmaStar SSC33x series
- [XM510 Installation](xm510.md) - XiongmaiTech XM510 series
- [XM530 Installation](xm530.md) - XiongmaiTech XM530 series

## Legacy Documentation

- [Old Installation Guides](old.md) - Previous installation methods
- [Old Full Manual](old-manual.md) - Comprehensive legacy manual

## Getting Help

If you encounter issues during installation, check our [troubleshooting section](../../troubleshooting/) or ask for help in our [Telegram community](https://openipc.org/our-channels).
