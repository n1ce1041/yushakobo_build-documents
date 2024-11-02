# Ergo68 Build Guide

![completed_assembly_Front](imgs/Completed_assembly_Front.jpg)
![completed_assembly_Back](imgs/Completed_assembly_Back.jpg)

Thank you for purchasing Ergo68.

**Please read this build guide to the end before starting the actual assembly. **

Please follow the assembly procedure.
If you have any questions about this procedure, please refer to the Yusha Kobo [Support Page](https://yushakobo.zendesk.com/hc/ja) and feel free to contact us.

## Notes

This kit requires the use of tools that may cause burns, such as cutting tools such as nippers and soldering irons, so please work with care.
The parts in the kit include small parts, so please store them out of reach of children.
We recommend that you clean the parts as needed as you work, as debris from the work, the legs of cut diodes, and the legs of pin headers may pierce the parts.
**Unplugging the TRS cable connecting the left and right sides while connected to the PC with a USB cable may cause a malfunction.**
**Never unplug the cable connecting the left and right sides while connected to the PC.**

## 1. Check the parts included in the kit

First, check that you have all the parts included in the kit.
If any parts are missing, we apologize for the inconvenience, but please contact us by selecting the category **"Missing/initial defects of purchased products, etc."** on Yusha Kobo's [Inquiry form](https://yushakobo.zendesk.com/hc/ja/requests/new).

|Name|Quantity|Image|
|---|---|---|
|PCB|2|![PCB](imgs/PCB.JPG)|
|Switch plate|2|![SW_Plate](imgs/SW_Plate.JPG)|
|Bottom plate|2|![Bottom_Plate](imgs/Bottom_Plate.JPG)|
|Cover plate|2|![Cover_Plate](imgs/Cover_Plate.JPG)|
|ProMicro|2|![ProMicro](imgs/ProMicro.JPG)|
|Conthrough (12 pin)|4|![Conthrough](imgs/Conthrough.JPG)|
|Reset switch Switch|2|![ResetSwitch](imgs/ResetSwitch.JPG)|
|TRRS jack|2|![TRRS](imgs/TRRS.JPG)|
|Screw (4mm)|28|![Screw](imgs/Screw.JPG)|
|Spacer (7mm)|14|![Spacer](imgs/Spacer7mm.JPG)|
|Spacer male/female (4mm)|8|![Spacer](imgs/Spacer4mm.JPG)|
|Rubber feet (small)|4|![Cushion](imgs/Cushion.JPG)|
|Rubber feet (large)|4|![Cushion](imgs/Cushion.JPG)|

### 1-1. Optional parts (battery parts kit)

|Name|Quantity|Image|
|---|---|---|
|Coin battery holder|4|![Battery](imgs/Battery.JPG)|
|Conthrough|1|![Conthrough2mm](imgs/Conthrough2mm.JPG)|
|Schottky barrier diode|4|![Diode](imgs/Diode.JPG)|
|Chip capacitor|2|![Condenser](imgs/Condenser.JPG)|
|Slide switch|2|![SlideSW](imgs/SlideSW.JPG)|

### 1-2. Optional parts (AAA battery parts kit)

|Name|Quantity|Image|
|---|---|---|
|AAA battery holder|4|![BatteryAAA](imgs/BatteryAAA.JPG)|
|Conthrough|1|![Conthrough2mm](imgs/Conthrough2mm.JPG)|
|Schottky barrier diode|4|![Diode](imgs/Diode.JPG)|
|Chip capacitor|2|![Condenser](i mgs/Condenser.JPG)|
|Slide switch|2|![SlideSW](imgs/SlideSW.JPG)|
|Cover plate (for AAA batteries)|2|![Cover_Plate_AAA](imgs/Cover_Plate_AAA.JPG)|
|Spacer, male and female (8mm)|8|![Spacer](imgs/XXXX.jpg)|
|Rubber feet (large)|4|![Cushion](imgs/Cushion.JPG)|

### 1-3. Optional parts (middle plate)

|Name|Quantity|Image|
|---|---|---|
|Middle plate (2mm)|2|![Middle2mm](imgs/Middle2mm.png)|
|Middle plate (5mm)|4|![Middle5mm](imgs/Middle5mm.png)|

## 2. Check for parts to prepare separately

Parts not included in the kit must be prepared separately.
Purchase them in advance and check that there are no missing parts before assembly.

|Name|Quantity|Notes|
|---|---|---|
|Key switches|68|Purchase here:(https://shop.yushakobo.jp/collections/all-switches/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)<br>Compatible with Cherry MX compatible switches only|
|Key caps|68|Purchase here:(https://shop.yushakobo.jp/collections/keycaps/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%AD%E3%83%BC%E3%82%AD%E3%83%A3%E3%83%83% E3%83%97)<br>Please check the key layout and keycap set carefully before purchasing|
|TRS cable or TRRS cable|1|Purchase here: (https://shop.yushakobo.jp/products/trrs_cable)<br>For LPME-IO, only TRRS cable is required<br>TRS has 3-pole terminals, TRRS has 4-pole terminals|
|USB cable|1|Purchase here: (https://shop.yushakobo.jp/products/usb-cable-micro-b-0-8m)<br>Please prepare according to the type of connector that the microcontroller supports<br>The included ProMicro requires a MicroB cable|

## Tools needed

|Name|Notes|
|---|---|
|Soldering iron|Preferably with temperature control function|
|Solder wire|Approximately 0.6mm~0.8mm diameter|
|Screwdriver|For tightening M2 size screws (#0)|
|Nippers|Preferably with a thin tip|

**We also have a [tool set](https://shop.yushakobo.jp/products/a9900to) available, so if you like, please purchase it along with the parts. **

## Assembly procedure

1. Soldering ProMicro and through connector
1. Soldering reset switch and TRRS jack
1. Writing firmware and checking operation
1. Break off the left and right board scrap boards
1. Attaching key switches to switch plate
1. Screwing spacers
1. Screwing bottom plate
1. Screwing cover plate
1. Attaching key caps
1. Attaching rubber feet
1. Changing key map
1. Soldering battery parts kit (optional)

## 1. Soldering ProMicro and through connector

**Check: Pay close attention to the front and back of ProMicro. **
**If you install it the other way around, it will be very difficult to remove the through connector. **

**Check: If you want wireless compatibility, use BLE Micro Pro instead of ProMicro, but soldering is not required. **
**See "EX1. Wireless compatibility" below instead. **

### 1-1. Inserting the connector through

Insert the pin socket from the **back** side of the board.

![ProMicro-1](imgs/ProMicro-1.JPG)

At this time, align the side of the connector through which the metal is visible as shown in the photo below.
**Check: If you are using ProMicro, leave the top pin of the board open and do not insert it. **

![ProMicro-2](imgs/ProMicro-2.JPG)

Also, connector throughs have a top and bottom.
The window through which the metal is visible is on either the top or bottom, so insert it so that the side closest to the top is the one you want.

![ProMicro-3](imgs/ProMicro-3.JPG)

### 1-2. Soldering the ProMicro

Insert the connector through the connector with the side where the ProMicro parts are visible facing up.

![ProMicro-4](imgs/ProMicro-4.JPG)

At this time, pay close attention to the orientation of the ProMicro.
The chip components of the ProMicro should be visible from the front side of the board.
It will be very difficult to remove the solder from the ProMicro later, so make sure to check that it is the same as the photo above.

When soldering, it is enough to feed about 2 to 3 mm of solder.
Place the soldering iron, wait 1 to 2 seconds, and then feed the solder.
Wait another 1 to 2 seconds before removing the solder, and then remove the soldering iron.
It is OK if it looks like the image below.

## 2. Soldering the reset switch and TRRS jack

**Point: The reset switch can be used without soldering. **
**It is rarely used, so if you do not plan to frequently rewrite the firmware, you can omit soldering. **
**Once the firmware has been written, the reset switch is not necessary to rewrite the keymap. **

Attach the reset switch and TRRS jack to the **back** of the board, opposite the ProMicro, where it says `Reset` and `TRRS`, and solder them from the **front**.

Left! [ResetTRRS-Left] (imgs/ResetTRRS-Left.JPG)

Right! [ResetTRRS-Right] (imgs/ResetTRRS-Right.JPG)

After soldering, cut it off with pliers and heat it again with a soldering iron to use it without scratching the desk.

! [ResetTRRS] (imgs/ResetTRRS.JPG)

## 3. Writing the firmware and checking operation

Ergo68 uses qmk_firmware as the firmware.

Use the Remap catalog function to write the firmware.
**Check:※For writing to BLE Micro Pro, see "EX1-5. Writing Firmware" at the end of this build guide.
