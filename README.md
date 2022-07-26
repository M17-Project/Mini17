<div align='center'>

[![GitHub issues](https://img.shields.io/github/issues/M17-Project/Mini17?style=flat-square)](https://github.com/M17-Project/Mini17/issues)
![GitHub pull requests](https://img.shields.io/github/issues-pr/M17-Project/Mini17?style=flat-square)
[![GitHub forks](https://img.shields.io/github/forks/M17-Project/Mini17?style=flat-square)](https://github.com/M17-Project/Mini17/network)
[![GitHub stars](https://img.shields.io/github/stars/M17-Project/Mini17?style=flat-square)](https://github.com/M17-Project/Mini17/stargazers)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/M17-Project/Mini17?style=flat-square)
![Maintenance](https://img.shields.io/maintenance/yes/2022?style=flat-square)
![Matrix](https://img.shields.io/matrix/m17-project:matrix.org?style=flat-square)
![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2Fm17_project)

</div>

# Mini17
Mini17 - QRP M17 handheld. Work in progress! The schematic is just a sketch for now. Stay tuned.

# About
The first handheld to suport M17 was our own [TR-9](https://github.com/M17-Project/TR-9). Unfortunately, the design has a minor flaw in the RF part and is very hard to assemble. After that, we tried modifying various radios with different outcomes. This is our new device - the **Mini17**. It's built around the [CC1200](https://www.ti.com/product/CC1200) RF chip, which does great job at receiving and transmitting M17 signals. The power output is limited to 16dBm (40mW), so it's a QRP radio. The idea is to build a small radio first and then add RF power amplifier stage later. A *Proof of Concept*, if you will. The design could even be extended to a mobile rig in the future.

# Hardware
The RF chip used is CC1200, MCU is STM32F427ZGT6. OLED display will probably be the same as in [Module17](https://github.com/M17-Project/Module_17).

# Firmware
[OpenRTX](https://github.com/OpenRTX/OpenRTX) - the Linux of amateur radio!
