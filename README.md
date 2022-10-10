# dotKeeb
A wireless, low profile ergonomic keyboard inspired by the dactyl.
**This is currently a work in progress. If you find this repo, please do not use the files here yet.**

ToDo : 
- improve formatting
- add circuit diagrams and build instructions
- add vendor links
- inspirations used

![Render](assets/render.png)

## Parts list
Here are the parts used in this build, along with links to where I purchased them from. I'd encourage you to try and get as much stuff from local vendors if possible.

- 50x Kailh choc switches and keycaps (MX-style switches are NOT compatible)
- 50x Kailh choc V1 hotswap sockets (Required for the hotswap version)
- 50x THT diodes
- 2x nice!nano microcontrollers
- 2x LiPo* batteries (100mAh is generally considered the minimum capacity)
- Wiring (I used 24 guage, single-core wire) You can use pretty much whatever you feel comfortable working with)
- 4x 4mm M3 heat-set screw inserts
- 4x 6mm M3 screws
- (Optional)** 2x nice!view displays
- (Optional)*** 2X Power switch
- (Optional)**** 6x small rubber feet

\* You could put in OLED displays instead of nice!views, although there would be some empty spaces in the slot. You could also run without displays at all. OLEDs will have much greater power consumption and so I'd recommend using much larger batteries for those.

\** LiPo batteries are the recommended type of batteries for use with the nice!nanos. You can still use and charge Li-ion batteries, but you may run into some issues. I personally use the Li-ion batteries I took out of my old Playstation Move controllers and they work fine.
If you want to use NiMH (Most commonly found as AA or AAA rechargeables), **DO NOT** plug in the usb with the batteries connected. You will have to charge them externally.

\*** The linked power switch is what the case was designed for. Others may not fit right. You could also forgo a power switch and rely on ZMK sleep, which is a valid option if you dont throw your keyboard into a bag or other place where keys can accidentally get pressed and wake the keyboard.

\**** You can use whatever method you want to get your keyboard to grip your table better. The linked rubber pads are what the plate was designed for

## Tools

- Soldering Iron - You don't need anything too fancy, just avoid those $10 kits. I used the Sequre D60 (TODO: link here)
- Solder - Use leaded solder if you can, it will make things significantly easier. I used 60/40 solder.
- Wire cutter / stripper - You could also use a pair of scissors but I wouldn't recommend it
- (Optional) Tweezers
- (optional) 3D printer - I say a printer is optional since you can make use of several online printing services if you don't own a printer, like JLCPCB. I used an Ender 3 V2, but depending on your region you may be able to find better printers that are also cheaper.
