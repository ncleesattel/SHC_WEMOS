# SHC_WEMOS
This is a handheld controller for TeenAstro.  
It features a 3.3V OLED 2.42" display, a joystick together with the WEMOS D1 mini MCU.  
The associated pcb can be ordered at JLCPCB fully assembled with smd parts and JST XH connectors.  
This reduces the amount of soldering to a minimum.  
_I also provide a design of an OLED pcb, that does not require smd soldering for the I2C use compared to the DIYmore pcb.  
Costs are about 3x, which makes it interesting only for hobbyists who want to avoid the smd solder._

## recommendations
* You’ll need to be able to solder a connection using a pinheader between the two pcbs.
* You’ll also need the soldering iron to melt the Ruthex nuts into place.
* The 3D prints do not need supports. Depending on your printer you may need to scale by 1.015 to account for thermal shrink.
* The cable length should be properly sized. The case does not have much room to accommodate long cables, however short cables make assembly and disassembly more difficult.
* Although the JST XH connectors can be attached to the cables without a crimp tool, I would highly recommend one for ease of life. You can thank me later.
*Check the functionality and connector sequence/polarity prior to assembly.

## components needed for build
* PCB group
  * pcb incl. smd parts of SHC
  * pcb for OLED 2.42“. Either mine with switches for I2C or DIYmore incl. smd modification
  * OLED 2.42“ display
  * metal bracket to attach OLED display to OLED pcb
* 3D print group
  * 3d print for pcb to display spacer
  * 3d print of bottom part
  * 3d print of top cover
  * Ruthex M3 nuts 2x
* Switches and cables
  * APEM 1000 joystick
  * APEM 1212 switch for shift
  * RAFI switches for focusser
  * SAL8 connector
  * JST XH connectors

## which files are needed for the...
* pcbs
  * SHC pcb --> jlcpcb folder
  * OLED pcb --> ../../oled242_pcb/jlcpcb folder
* 3D prints
  * SHC bottom case --> models folder
  * SHC top case --> models folder
  * SHC display to pcb spacer --> models folder
 
 ## associated CAD files
The CAD files have been mostly created in Fusion 360 with OEM parts imported where available. 

## pictures of the SHC
![SHC_WEMOS 3D view](/Astro/SHC_WEMOS/img/WEMOS_SHC_3d_01.JPG "WEMOS_SHC_3d_01")

![SHC_WEMOS pcb view](/Astro/SHC_WEMOS/img/WEMOS_SHC_3d_02.JPG "WEMOS_SHC_3d_02")

![SHC_WEMOS assembly step 01](/Astro/SHC_WEMOS/img/WEMOS_SHC_assy_01.JPG "WEMOS_SHC_assy_01")

![SHC_WEMOS assembly step 02](/Astro/SHC_WEMOS/img/WEMOS_SHC_assy_02.JPG "WEMOS_SHC_assy_02")

![SHC_WEMOS assembly step 03](/Astro/SHC_WEMOS/img/WEMOS_SHC_assy_03.JPG "WEMOS_SHC_assy_03")

![SHC_WEMOS assembly step 04](/Astro/SHC_WEMOS/img/WEMOS_SHC_assy_04.JPG "WEMOS_SHC_assy_04")

![SHC_WEMOS assembly step 05](/Astro/SHC_WEMOS/img/WEMOS_SHC_assy_05.JPG "WEMOS_SHC_assy_05")

![SHC_WEMOS side view cut](/Astro/SHC_WEMOS/img/WEMOS_SHC_cut_01.JPG "WEMOS_SHC_cut_01")

![SHC_WEMOS side view](/Astro/SHC_WEMOS/img/WEMOS_SHC_side_01.JPG "WEMOS_SHC_side_01")

![SHC_WEMOS top view](/Astro/SHC_WEMOS/img/WEMOS_SHC_top_01.JPG "WEMOS_SHC_top_01")


