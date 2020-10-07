# Hackintosh-Gigabyte-B460M-Aorus-Pro-Intel-i5-10400
 Successful Hackintosh build on a custom PC

## Table of Contents:
- [Hackintosh-Gigabyte-B460M-Aorus-Pro-Intel-i5-10400](#hackintosh-gigabyte-b460m-aorus-pro-intel-i5-10400)
  - [Table of Contents:](#table-of-contents)
  - [Info](#info)
  - [Versions](#versions)
  - [Working](#working)
  - [Not working](#not-working)
  - [Screenshots](#screenshots)
  - [Useful tools:](#useful-tools)
  - [Change:](#change)

## Info

Parts|Type|Links|
--:|:--|:--|
**Motherboard**|Gigabyte B460M Aorus Pro|[Link](https://www.gigabyte.com/Motherboard/B460M-AORUS-PRO-rev-10#kf)
**CPU**|Intel i5 10400|[Link](https://ark.intel.com/content/www/us/en/ark/products/199271/intel-core-i5-10400-processor-12m-cache-up-to-4-30-ghz.html)
**RAM**|GSkills Aegis DDR4-3000MHz 1x16GB |[Link](https://www.gskill.com/product/165/185/1535968303/F4-3000C16S-16GISBAegis-DDR4DDR4-3000MHz-CL16-18-18-38-1.35V16GB-(1x16GB))
**SSD**|NVMe TOSHIBA THNSN51T02DU7 1024GB||
**PSU**|FSP HyperM 700W|[Link]()

## Versions
- BIOS F3
- AppleALC 1.5.3
- IntelMausiEthernet 2.5.1d1
- Lilu 1.4.8
- OpenCore 0.61
- VirtualSMC 1.1.7
- WhateverGreen 1.4.3

## Working
- 
- FireVault
- DualBoot (Windows 10 v2004)
- Audio (Realtek® ALC1200 codec)
- Front Audio
- Ethernet (Intel® Ethernet Connection I219V12)
- All USB (not all tested, front USB works flawlessly)
- HDMI/DP
- iMessage
- SideCar

## Not working
- wake from sleep
## Screenshots
<center> ![about](/images/about.png "About") </center>
<center> ![about](/images/memory.png "Memory") </center>
<center> ![about](/images/neofetch.png "neofetch") </center>
<center> ![about](/images/geekbench-device "Geekbench") </center>

## Useful tools:
- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [Hackintool](https://github.com/headkaze/Hackintool)
- [MLB generator](https://gist.github.com/graphis/688e2caa200d2b4182f7b9cc20a14731)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- [ProperTree](https://github.com/corpnewt/ProperTree)

## Change:
Please change MLB, SystemSerialNumber, SystemUUID