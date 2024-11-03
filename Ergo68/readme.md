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

**Point: You can use the reset switch without soldering. **
**You won't need to use it often, so you can skip soldering if you don't plan to update the firmware frequently. **
**Note that once you've written the firmware, you won't need the reset switch to update the keymap. **

Attach the reset switch and TRRS jack to the **back** of the board, opposite the ProMicro, where it says `Reset` and `TRRS`, and solder from the **front**.

Left side! [ResetTRRS-Left] (imgs/ResetTRRS-Left.JPG)
Right side! [ResetTRRS-Right] (imgs/ResetTRRS-Right.JPG)

After soldering, you can cut it off with pliers and heat it again with a soldering iron to use it without scratching the desk.

![ResetTRRS](imgs/ResetTRRS.JPG)

## 3. Firmware writing and operation check

Ergo68 uses qmk_firmware as the firmware.

Firmware is written using the catalog function of Remap.
**Check:※For writing to BLE Micro Pro, refer to `EX1-5. Firmware writing` at the end of this build guide. **

https://remap-keys.app/catalog/qIgO7rOq7GMRsGf6QhlY/firmware

Once firmware writing is complete, open the Remap configurator screen.

https://remap-keys.app/configure

Click FLASH.

![Remap-1](imgs/Remap-1.png)

Select "caterina" for normal ProMicro and "dfu" for Elite-C, then click FLASH.
*When writing using "dfu", you may need to use a separate tool called Zadig.

![Remap-2](imgs/Remap-2.png)

Check that "Arduino Micro" is displayed in the small window as shown below.
If it is not displayed, try changing the cable or the port to connect to.

![Remap-6](imgs/Remap-6.png)

When you press the reset switch, you will hear a sound like a USB device being removed, so check that the port number of the Arduino Micro in the small window has changed, and quickly click "Connect".
(In the example of this build guide, COM17 changes to COM18)
If the port number does not change, try resetting twice quickly.

![Remap-7](imgs/Remap-7.png)

When the firmware writing is complete, "successfully" will be displayed at the end of the message as shown below.
**Check:If you do not use a normal ProMicro such as Elite-C, it may fail. **
**If you are using Elite-C etc., change Bootloader to dfu and change the USB mode of dfu according to the instructions in Remap. **

![Remap-8](imgs/Remap-8.png)

First, check if all the LEDs are on.

![Remap-9](imgs/Remap-9.JPG)

![Remap-10](imgs/Remap-10.JPG)

**Point: The LEDs on the top left and right are indicators. **
**The left side is CapsLock, NumLock, ScreenLock. **
**The right side is the layer state. **
**However, it is normal if these indicators are off when the PC is connected. **

If it is recognized correctly by Remap, open the test mode and check the continuity by touching the metal part of the switch socket with tweezers.

![Remap-3](imgs/Remap-3.png)

![Remap-4](imgs/Remap-4.JPG)

If everything is normal, all the keys will be blue as shown below.

![Remap-5](imgs/Remap-5.png)

## 4. Break off the scrap boards on the left and right sides of the board

Break off the scrap boards on the left and right sides of the board.

![PCB-1](imgs/PCB-1.JPG)

**Check: If you apply too much force to the entire board when folding, the switch socket may come off. **
**If it is difficult to fold, trace it with a cutter or cut it with pliers. **

![PCB-2](imgs/PCB-2.JPG)

## 5. Attaching the key switch to the switch plate

Attach the key switch to the switch plate.
First, fit the switches into the four corners of the switch plate.

![SW-1](imgs/SW-1.JPG)

**Check: Only the orientation of the switch on the parent key part is different. **
**Compare it to the orientation of the switch socket on the board and fit it into the switch plate in the correct orientation. **

![SW-2](imgs/SW-2.JPG)

**Check: Check that the switch is properly fitted into the switch plate. **

![SW-3](imgs/SW-3.JPG)

**Check: If installing the middle plate, sandwich the middle plate (2mm) between the board and the switch plate. **
Align the switch plate with the board and fit the switch terminal into the switch socket on the board.
**Check: Before inserting it into the switch socket, check again that the switch is facing correctly and that the pins are not bent. **

![SW-4](imgs/SW-4.JPG)

**Check: Insert the switch all the way in. **

![SW-5](imgs/SW-5.JPG)

Install all the switches.
**Check: Pay attention to the orientation of the switches. **
**Point: At this point, it is a good idea to test it again with Remap. **

![SW-6](imgs/SW-6.JPG)

## 6. Screwing the spacer

Attach the spacer (7mm) to the switch plate.
Place the spacer in the screw hole on the back of the switch plate, and screw it from the front of the switch plate while holding it down with your finger.
**Point: When attaching the middle plate, overlapping a 5mm plate will prevent the spacer from spinning freely and make it easier to tighten. **
**Point: If it is difficult to fix the spacer with your finger, lightly stick it with masking tape to avoid frustration. **

![Screw-1](imgs/Screw-1.JPG)
![Screw-2](imgs/Screw-2.JPG)
![Screw-3](imgs/Screw-3.JPG)
![Screw-4](imgs/Screw-4.JPG)

## 7. Screw the bottom plate

**Point: If you are using wireless compatibility, refer to EX1. Wireless compatibility and install the battery parts before the bottom plate. **

Put the bottom plate on and screw the three places on the lower half.

![Screw-5](imgs/Screw-5.JPG)

Then, screw the male/female spacers (4mm) into the four places on the upper half with your fingers.

![Screw-6](imgs/Screw-6.JPG)

## 8. Screwing the cover plate

Place the cover plate on top of the spacer (male/female) (4mm) on the top half of the bottom plate and screw it in place.
**Point: If you are using a connector through the ProMicro, it is quite common that the connector will come loose when you plug in and unplug the USB cable, causing the keys to stop working. **
**To prevent this problem, there is a method to prevent the ProMicro and cover plate from coming loose by attaching cushion rubber to them. **
**If you frequently plug in and unplug the USB cable, please consider this. **

![Screw-7](imgs/Screw-7.JPG)

## 9. Attaching the keycaps

Attach the prepared keycaps.

## 10. Attaching the rubber feet

Attach the rubber feet to a total of 8 places on the left and right sides of the bottom plate and cover plate.
Attach the taller rubber feet to the cover plate side.
Please refer to the circular print on the bottom plate and cover plate for the placement.

## 11. Change the key map

Change the key map to suit your needs.

Remap is a convenient way to change the key map.

https://remap-keys.app/configure

Please refer to the following site for instructions on how to use Remap.

https://salicylic-acid3.hatenablog.com/entry/remap-manual

## EX1. Wireless compatibility

By using BLE Micro Pro instead of ProMicro, you can make a wireless connection using Bluetooth.

Even if you just replace ProMicro, you can power it with a mobile battery, but by using the battery board parts for BLE Micro Pro, you can build in a coin battery (CR1632).

In addition to BLE Micro Pro, you can also use partial wireless using a **4-pole** TRRS cable between the left and right sides using [LPME-IO](https://shop.yushakobo.jp/products/lpme-io2a).

However, in both the fully wireless system using two BLE Micro Pros and the partial wireless system combining BLE Micro Pro and LPME-IO, only the left keyboard can be connected to the PC.
The right keyboard only transmits key presses to the left keyboard.
Also, in the case of a wireless connection using BLE Micro Pro, please note that the LED only lights up when powered by USB.

### EX1-1. Installing the BLE Micro Pro

**Check: If you use a through connector for BLE Micro Pro, soldering is not required. **
**The same applies to LPME-IO, but a jumper is required to the LPME-IO microcontroller board. **

If you use a 13-pin through connector (sold separately), use it as is. (Recommended)
If you want to use the 12-pin through connector included in the kit with BLE Micro Pro, install it as shown in the photo below. (Same for LPME-IO)
The BLE Micro Pro has a pin for the battery on the top right (with the USB connector facing up), so offset one pin on the right side only to attach the connector through.
Align the connector in the same direction as when installing the ProMicro.

Left side! [BMP-1] (imgs/BMP-1.JPG)

Right side! [BMP-2] (imgs/BMP-2.JPG)
**※The example in this photo is for when using a 12-pin connector through. **
**No offset is required if using a 13-pin connector through. **

Left side BMP installation example! [BMP-3] (imgs/BMP-3.JPG)
Right side BMP installation example! [BMP-4] (imgs/BMP-4.JPG)

LPME-IO jumper part! [LPME-IO-1] (imgs/LPME-IO-1.png)
The jumper part of the LPME-IO may be slightly raised and short with the socket, so it is best to insulate it with tape.
! [LPME-IO-2] (imgs/LPME-IO-2.png)
LPME-IO installation example! [LPME-IO-3] (imgs/LPME-IO-3.png)

### EX1-2. Soldering the battery parts

The battery parts are soldered to the bottom plate.
Before soldering, it is a good idea to attach masking tape to distinguish between left and right so that you don't mix them up.
**Check: If you are using LPME-IO, there is no need to solder the battery parts on the LPME-IO side (right side). **

![BMP-5](imgs/BMP-5.JPG)
![BMP-6](imgs/BMP-6.JPG)

First, attach the capacitor and Schottky barrier diode to the front side of the bottom plate (the side with the masking tape, which will be the board side).

These two parts are surface-mounted parts (parts that are attached to the surface of the board), so a little skill is required.

First, put a little solder called spare solder on the board.

![BMP-7](imgs/BMP-7.JPG)

Then, hold the diode and capacitor with tweezers and place them on the board while melting the spare solder with a soldering iron.

![BMP-8](imgs/BMP-8.JPG)

Once the spare solder has melted and is temporarily fixed, solder the legs of the diode on the other side.
If the solder becomes sharp because it is heated for too long, it will be easier to do it by adding more flux.

![BMP-9](imgs/BMP-9.JPG)

Next, solder the slide switch to the back side of the bottom plate (the side without the masking tape, which will be the bottom side).
Insert the slide switch into the hole with the knob facing down and temporarily fix it with masking tape.

![BMP-10](imgs/BMP-10.JPG)

Turn it over and cut the legs of the slide switch close to the board and solder them.

![BMP-11](imgs/BMP-11.JPG)
![BMP-12](imgs/BMP-12.JPG)
![BMP-13](imgs/BMP-13.JPG)

Finally, solder the battery holder to the back side of the bottom plate (the side without the masking tape, which will be the bottom side).
The coin battery holder has a top and bottom, so please refer to the orientation in the photo below.

![BMP-14](imgs/BMP-14.JPG)

When soldering the board upside down, hold the holder down with masking tape or something similar to prevent it from floating away.

![BMP-16](imgs/BMP-16.JPG)

The same applies to the AAA battery holder.
The AAA battery holder has a positive and negative pole on the left and right, so be careful of the orientation.

![BMP-15](imgs/BMP-15.JPG)

Flip this over as well, cut the legs as close as possible, and solder them.
If they float, it will be easier to hold them down with masking tape.

![BMP-17](imgs/BMP-17.JPG)

### EX1-3. Preparing the 2-pin connector

The bottom plate where the battery will be mounted and the board where the microcontroller will be mounted will be connected with a 2mm 2-pin connector.
The connector can be easily cut with pliers or a cutter, so cut out 2 pins from the 12-pin connector.
It is very easy to cut it directly above the hole in the connector.

![BMP-18](imgs/BMP-18.JPG)
![BMP-19](imgs/BMP-19.JPG)

Insert the cut 2-pin connector into the connection pin on the board.
It is located near the BLE Micro Pro.
The orientation does not matter.

![BMP-20](imgs/BMP-20.JPG)

### EX1-4. Connecting the bottom plate

Cover the bottom plate carefully, being careful not to bend the 2-pin connector.

![BMP-21](imgs/BMP-21.JPG)

For coin battery cases, the subsequent assembly process is the same as for ProMicro.
When using a AAA battery case, use a combination of a male-female spacer (4mm) and a male-female spacer (7mm).
First, screw the 7mm spacer into the bottom plate, then screw the 4mm spacer on top of it.
Then, use a cover plate with a hole for a AAA battery.
Use the large rubber feet for this purpose.

### EX1-5. Writing the firmware

Write the firmware from the BLE Micro Pro Web Configurator below.

https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/

Run the BLE Micro Pro Web Configurator from the top down.
After running the BLE Micro Pro Web Configurator from the top down, select "Ergo68" from the "Write settings for each keyboard" button and write it.

![BMP-22](imgs/BMP-22.png)
![BMP-23](imgs/BMP-23.png)

After writing the settings, apply the default keymap from Remap or the BLE Micro Pro repository.

![BMP-22](imgs/BMP-24.png)
![BMP-23](imgs/BMP-25.png)

Or download the default keymap for Ergo68 for BLE Micro Pro from GitHub and drag and drop it onto the removable media of the BLE Micro Pro.
https://github.com/sekigon-gonnoc/BLE-Micro-Pro/blob/master/AboutDefaultFirmware/keyboards/ergo68/KEYMAP.JSN

After writing, follow the same procedure as "3. Soldering the reset switch".

**Point: For issues specific to BLE Micro Pro, such as unstable Bluetooth connection and inability to rewrite keymap, please check the FAQ here. **
