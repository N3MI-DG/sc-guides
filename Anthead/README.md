# Anthead Assembly Guide
<img src="images/Hero.png" />
The Anthead toolhead can be configured in various ways. This guide covers the standard flow version with several Stealthchanger community modifications, which provide a solid foundation for a reliable toolchanger.

---

## Table of Contents

- [BOM](#bom)
- [LED Assembly (Optional)](#led-assembly-optional)
- [Hotend Assembly](#hotend-assembly)
- [Main Body Assembly](#main-body-assembly)
- [Secure Hotend Assembly to the Stealthchanger Backplate](#secure-hotend-assembly-to-the-stealthchanger-backplate)
- [Secure the Main Body to the Hotend Assembly](#secure-the-main-body-to-the-hotend-assembly)
- [Assemble Fan Ducts](#assemble-fan-ducts)
- [Attach Fan Ducts](#attach-fan-ducts)
- [Install Extruder](#install-extruder)
- [PCB Mount](#pcb-mount)
- [Electronics](#electronics)
- [Credits](#credits)

---


## BOM

- 6x M3x6 BHCS Screws
- 10x M3x8 BHCS Screws
- 4x M3x12 BHCS Screws
- 2x M3x14 BHCS Screws
- 4x M3x8 SHCS Screws
- 1x M3x12 SHCS Screw
- 2x M3x28 SHCS Screws
- 19x M3 Heat Insert
- 2x 6x3mm N52 Magnets
- 1x Voron Revo Hotend
- 1x Orbitor 2.x Extruder
- 1x Nitehawk36 Toolhead Board
- 1x 25x10mm Radial Fan
- 2x 40x10mm Centrifugal/Blower Fan
- 1x 4x2mm PTFE ~40mm Long

If you wish to add Logo and nozzle LEDs, the following is also required.

- 3x SK6812 RGBW LED boards

---

## LED Assembly (Optional)

**1** - Solder pins/wires to the 3 SK6812 LED boards. The first LED in the chain should be ~60mm centers from the second LED. The third LED should be 12.5 centers from the second. You will need ~150mm of wire to route to your toolhead board. 
<img src="images/LED 1.1.png" />

**2** - Insert the second and third LED in to the nozzle LED carrier.(Wires removed from image for clarity)
<img src="images/LED 1.2.png" />

**3** - Install the Nozzle LED retainer by inserting the little hook in the retianing hole and press the retainer down against the LED boards. The LED carrier should flex and then capture the retainer in place.
<img src="images/LED 1.3.png" />

**4** - Slide the logo LED carrier over the remaining LED and put this assembly aside for now. It will be installed later.
<img src="images/LED 1.4.png" />

## Hotend Assembly

**1** - Install 4 M3 heat inserts in to the hotend mount. 
<img src="images/1.1.png" />

**2** - Install the hotend in to the hotend mount using 4 M3x8 SHCS screws.
<img src="images/1.2.png" />

**3** - Install 25x10 radial fan on the front of the hotend mount using 2 M3x14 BHCS screws. Take note of the orientation of the fan. The wires should be on the bottom right.
<img src="images/1.3.png" />

---

## Main Body Assembly

**1** - Install 7 M3 heat inserts in to the main body.  
<img src="images/2.1.png" />

**2** - Install the fan grill in to the main body by angling it in place so that the top of the grill gets inserted first. Be careful not to snap the side of the main body; they can be very fragile at this stage.
<img src="images/2.2.png" />

**LED VERSION ONLY**

**3** - Install the logo light shield and diffuser.
<img src="images/LED 2.1.png" />

**4** - Install the nozzle LED carrier in to the notches in the bottom of the main body. It may not stay in place just yet. It will be locked in place when the hotend assembly gets mounted.
<img src="images/LED 2.2.png" />

**5** - Install the Logo LED carrier. The wires between the nozzle and logo need to hug the wall of the main body and the wires going to the logo LED get routed through the cable channel in the top of the main body.
<img src="images/LED 2.3.png" />

---

## Secure Hotend Assembly to the Stealthchanger Backplate

**1** - Place a M3x12 SHCS screw head first in to the captive hole on the back plate.
<img src="images/3.1.png" />

**2** - Place the Stealthchanger Anthead spacer over the M3 screw ensuring the side wire channels align with backplate.
<img src="images/3.2.png" />

**3** - Secure the hotend assembly constructed in step 1 to the backplate and spacer using 2 M3x28 SHCS screws making sure not to pinch any wires. Route the hotend cables for the hotend to the left side for now. They will be secured later. If you opted for the LED version the cables will exit through the opening in the top.
<img src="images/3.3.png" />

---

## Secure the Main Body to the Hotend Assembly

**1** - Feed the cable for the hotend fan through the hole on the right side of the main body (from the inside). Secure the main body to the hotend assembly using 2 M3x6 BHCS screws and engage the captured M3x12 SHCS screw by putting an allen key through the small hole in the backplate (If you have a spacer with a cut out for the extruder, do not tighten the 12mm screw fully just yet). 
<img src="images/4.1.png" />

---

## Assemble Fan Ducts

**1** - Insert a M3 heat insert in to each duct and glue a 6x3 magnet in the bottom of each duct. 
<img src="images/5.1.png" />

**2** - Install a 40x10 blower fan into each duct. Depending on the make of fan you have, it may be necessary to remove the fan's cover before installation. Optionally you can secure each fan with 2 M2x6 self tapping screws. Route the wires for the left fan along the back of the fan and out the side of the duct.
<img src="images/5.2.png" />

---

## Attach Fan Ducts

**1** - Starting by hooking the bottom of the fan duct on the bottom of the main body, secure both fan ducts assembled in step 5 on to the main body assembly from step 4 using 4 M3x6 BHCS screws. Make sure the cable for the left fan is sitting if the cable channel in the main body (similar to how the hotend fan wires were routed previously).
<img src="images/6.1.png" />

**2** - Secure the bottom of the ducts to the backplate using 2 M3x8 BHCS screws.
<img src="images/6.2.png" />

**Check assembly** -  make sure ducts are hooked in on the bottom correctly, there are no pinched wires and the fans can move freely.

---

## Install Extruder

**1** - Install 4x2mm PTFE tube into the top of the main body making sure it bottoms out in the hotend. The PTFE needs to be cut to length to suit your extruder and have the inner diameter chamfered on the top.
<img src="images/7.1.png" />

**2** - Install the extruder on to the main body with 2 M3x12 BHCS screws. 
<img src="images/7.2.png" />

---

## PCB Mount

**1** -Install 2 M3 heat inserts into the PCB mount.
<img src="images/8.1.png" />

**2** - Install 2 M3 heat inserts into each PCB mount spacer.
<img src="images/8.2.png" />

**3** - Screw the 2 PCB mount spacers on to the back of the extruder's stepper motor and attach the PCB mount using 4 M3x8 BHCS screws.
<img src="images/8.3.png" />

---

## Electronics

**1** - Tighten the M3x12 screw that was captured in Step 3 if it has not been fully tightened already. This is also a good time to tidy up some of the wiring. There is more than one way to do this. Here is one example: 
You can secure the wires coming out of the Anthead to either side with zip ties using the supplied channels (RED) and pass the fan, LED and thermistor wires through the hole underneath the PCB mount (GREEN). The heater cable can be passed through the bottom hook (BLUE).
<img src="images/9.1.png" />

**2** - Install the OptoTap PCB to the back plate using 2 M3x8 BHCS screws. If you feel like the PCB will be pinching any wires, reroute them to the side hooks.
<img src="images/9.2.png" />

**3A** - If you have the extended tabs on your toolhead board, secure the bottom of the toolhead board to the PCB mount using 2 M3x8 BHCS screws. 
**3B** - Secure the toolhead board to the PCB mount using 2 M3x12 BHCS screws.
<img src="images/9.3.png" />

**4** - Wire up your toolhead. Thanks to LDO for the following image.
<image src="images/nh36-revc-pinout-20250331.jpg" />

**5** - If you held your toolhead board in place using the 2 M3x12 BHCS screws and want to install the toolhead board cover, remove them now. Install 2 M3x12 BHCS screws in to the toolhead board cover before securing the cover to the PCB mount through the toolhead board mounting holes. These screws can be a tight fit, you will most likely need tweezers or small needle nose pliers to hold them in place.
<img src="images/9.5.png" />

**6** - Plug your umbilical cable into the top of the toolhead board and secure the umbilical cable to the PCB mount using the TPU sock.
<img src="images/9.6.png" />

---

## Credits

- **hartk1213** - Anthead design  
- **TheSin-** - PCB mount  
- **Nic335** - TPU sock  
- **N3MI-DG** - Nozzle LEDs, toolhead board cover, and PCB mount spacers  
- **Draftshift Design** - Stealthchanger backplate  
- **LDO** - Orbiter extruder and Nitehawk36 PCB  
- **E3D/Voron Design** - Revo Voron hotend
