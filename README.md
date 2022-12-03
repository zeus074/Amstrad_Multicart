# AMSTRAD GX4000 / CPC464+ MULTICART
16 IN 1

This cartridge allows programs to run on the Amstrad GX4000 or CPC464+ computer

It uses two 27C801 ROMs to store up to 8 programs of 128kb each.

With the switch on top of the cartridge it is possible to select which rom to use, while with the dipswitch the bank is selected from 0 to 7, for a total of 16 games.

Amstrad uses a protection system for these cartridges, you can use the original chip **acid** (taken from another cartridge) or a 74HC112N flip-flop.

PCB:

![alt text](https://github.com/zeus074/Amstrad_Multicart/blob/main/IMG/multicart_pcb.jpg)

Prototipe:

![alt text](https://github.com/zeus074/Amstrad_Multicart/blob/main/IMG/multicart_proto.jpg)

:coffee: if you want the PCB, please support me and follow this link : <a href="https://www.pcbway.com/project/shareproject/Dram_tester_for_4116_4164_256_and_4532_d6b7143c.html" target="_NEW">PCBWAY!</a>


You can find the video of this project on the Retrofixer channel: link

Please consider subscribing to the channel, it's free and helps us to improve and always offer you new videos and more!


**Components:**

R1,R2,R3,R4,R5: 4K7

R6: 10K

C1,C2,C3,C4: 100nF ceramic

N.2 EEprom 27C801

Mount Amstrad 40908 or the 74HC112N (Do not use them together)

SW1: Dip-switch (3pin)

SW2: Slide switch 2 position (DPDT)

*Resistors r4 or r5 can not be mounted if the respective inputs A17 or A18 are used by the console and not managed by the dipswitch


**Realization:**

the gx4000 has a system to prevent the insertion of the cartridge with the console on and removal, it is necessary that the flaps of the slot are all open otherwise the switch remains blocked. 

To overcome this you can enlarge them by hand or make a case for the cartridge, if you make the case, the chips must be soldered on the pcb without a socket, otherwise the card will be too thick.

Behind the card there are 2 jumpers JP17 and JP18 which can be closed in position SW or A17,A18.

If they are to be used for 128k games, they must be set to SW, so 8 games can be managed in the dipswitch.

If you use larger roms these can be managed by the console by making the jumper between the central pin and the relative input.

This change (JP17,JP18) affects both roms.

You can find schemnatic and BOM in the relative folders and a sample sticker for the enclosure in the IMG folder.

**Final cartridge:**

![alt text](https://github.com/zeus074/Amstrad_Multicart/blob/main/IMG/cart-gx4000.jpg)

Ofcourse! This case is in the 3D_Print folder.

Subscribe to my channel Retrofixer https://www.youtube.com/@retrofixer to keep us going in this work.

You can print ready-made pcb on PCBWAY! https://www.pcbway.com/project/shareproject/Amstrad_GX4000_multicart_or_CPC464_PULS_3cb5d5b8.html

**Low price for a great cart!:**
Costs for the realization: (shipping not included and prices taken at the time of production and may no longer be true)
2x27C801 =€4.43 (Aliexpress)

6xResistor=€0,72 (Mouser)

4xCapacitor=€1.08 (Mouser)

1x74HC112N=€0,73 (Mouser)


Enjoy!
