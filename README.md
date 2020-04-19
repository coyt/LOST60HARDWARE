# LOST60HARDWARE
Hardware design files for LOST60 Bluetooth Mechanical Keyboard

<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60HARDWARE/blob/master/pictures/keyboardUnderlighting.gif?raw=true"/>
</p>

#### LOST60 PCB Version 2.0 (SPRING 2020)
<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60/blob/master/KeyboardV2.jpg"/>
</p>

#### LOST60 PCB Version 1.0 (FALL 2019)
<p align="center">
<img width="800px" src="https://raw.githubusercontent.com/coyt/LOST60/master/keyboardpic.jpg"/>
</p>

*The Ultimate Hackable Bluetooth Mechanical Keyboard*

#### Overview

Hardware design files for the LOST60 Bluetooth 60% Mechanical Keyboard PCB. The PCB utilizes a Nordic Semiconductor [nrf52840 bluetooth SoC](https://www.nordicsemi.com/?sc_itemid=%7B2DC10BA5-A76E-40F8-836E-E2FC65803A71%7D) (Rigado BMD-340 module) as the sole processor.


#### PCB Artwork
<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60HARDWARE/blob/master/pictures/lost60eaglelayout.png?raw=true"/>
</p>


#### 3D Modeling
<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60HARDWARE/blob/master/pictures/lost60v2slanted.PNG?raw=true"/>
</p>

<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60HARDWARE/blob/master/pictures/LOST60V2Bottom.PNG?raw=true"/>
</p>

<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60HARDWARE/blob/master/pictures/lost60V2%20v26.png?raw=true"/>
</p>


#### Version 2.0 System Diagram

<p align="center">
<img width="800px" src="https://github.com/coyt/LOST60/blob/master/BLEKeyboardV2SystemDiagram.jpg"/>
</p>

#### Hardware Features
* 60% Mechanical Keyboard design based on GH60 Layout
* USBC connector
* Bluetooth 5.0 support
* Full RGB underlighting with "neopixels"
* Independently addressable single color key backlingting
* Qi wireless charging
* Advanced battery charging and management circuitry
* Rotary encoder and TWO speakers for Synthesizer features (under development)
* Several expansion ports (QUIIC, GROVE, CUSTOM)

#### Planned Hardware Updates

- [x] Add coulomb counting IC / improve voltage and power measurement   (Complete in V2.0)
- [ ] Improve backlighting LED brightness 
- [x] Extend USB C connector out a bit                                  (Complete in V2.0)
- [x] Fix underlighting load switch fly wire                            (Complete in V2.0)
- [x] Fix LiPo charger ground pour problem & improve charge rate        (Complete in V2.0)
- [x] Remove onboard Lithium protection IC                              (Complete in V2.0)
- [ ] Add physical power switch connection point 
- [ ] Change wiring so I/O emulates Feather nrf52840 board
- [x] Add QSPI memory chip                                              (Complete in V2.0)

#### Development Setup

This design was created using Eagle PCB for schematic capture and PCB layout and routing. Fusion 360 was used to generate CAD model of board before manufacture. 
