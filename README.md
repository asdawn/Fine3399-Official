# Fine3399 Official

 Fine3399 - one final RK3399 geek board

```Java
try{
    Get a machine with sw799 core board;
    Disassembly the machine;
}catch(the core board){
    Modify the circuit to enable PCIE 2.0 (optional);
    Change the EMMC to get large storage space (optional);
    Buy a Fine3399 motherboard;
    Assemble them;
}finally{
    Have fun with your Fine3399!
}

```

## 1. What is Fine3399

Fine3399 is a multi-purpose embedded board designed by rumu3f.

### 1.1 Features

feature| details
CPU | RK3399 (A72\*2+A53\*4)
RAM | 4GB 
EMMC| 8GB/16GB/64GB/128GB
LAN1| gigabyte Ethernet 
LAN2| gigabyte Ethernet（USB3.0）
HDMI| HDMI 2.0
TF| TF-card slot
NVME| M key, PCIE 2.0 2X
USB | USB3.0*1, Type C*1(OTG)
SPI | flash\*0/\*1, LCD\*0/\*1
FAN | 4pin PWM slot
POWER| DC 12V, 5521 slot
KEY | power key and recovery key
LED | power LED
RTC | RTC battery slot, 2pin


## 2. How to use

(1) burn a firmware

(2) enjoy it

## 3. Where to buy

**You can buy a ready to use board from [Jack's shop](https://jack).**

 Otherwise you can get a core board and a mother-board separately.

### 3.1 sw799 core board

(1) Buy a ready to use board from Jack's Grocery Store

[sw799 core board with 4GB RAM and 8GB EMMC](https://jack)

[sw799 core board with 4GB RAM and 16GB EMMC](https://jack)

[sw799 core board with 4GB RAM and 64GB EMMC](https://jack)

[sw799 core board with 4GB RAM and 128GB EMMC](https://jack)

(2) Buy a post-market machine with sw799 core board\*

Know models:

+ Bozz F630D
+ Bozz F639D


\* you still have to modify it to enable PCIE.

(3) Buy a new core board from bozztek\*

Bozztek is the designer and producer of the sw799 core board. If you need a B2B contact, maybe you have to contact [bozztek](http://www.bozztek.com/).

\* you still have to modify it to enable PCIE.

### 3.2 Fine3399 motherboard

(1) Buy a ready to use board

[Get it from Jack's Grocery Store](https://jack)

(2) Buy DIY kit

With the DIY kit, you can build a Fine3399 motherboard with your own hand.
It is not quite easy, however this is the way of geek.

[Get it from Jack's Grocery Store](https://jack)

## 4. Known problems & Trouble shootings

## 5. Firmware and source code

### 5.1 Firmware

Firmware | Status | Downloads | Boot media
---------|--------|-----------|-----------
Armbian | usable, not perfect | TF card, EMMC
Android | usable, not perfect | TF card, EMMC
OpenWRT | usable, not perfect | TF card, EMMC
UEFI OS\* | not implemented | SPI flash

\* Morden u-boot support some UEFI features, you can find the best practices on RK3399 boards from [ARM's git](https://gitlab.arm.com/systemready/firmware-build/rk3399-manifest/-/blob/main/README.md). These boards can boot from Generic ARM64 OS images incude Ubuntu, Debian, SUSE, Fedora and so on. In the future we'll try to enable similar features with u-boot in SPI flash, there would be a wide variety of OSs to choose from.

### 5.2 Source code

(1) Device tree

dts file will be released soon.

(2) Schematics

Schematic diagrams will be released later.

(3) SDKs

SDK for the SPI LCD will be released soon.