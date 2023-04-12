# STM32F411-Custom-Kit

#### NOTE (as of April 12th 2023)
#### By Kicad ERC and DRC this board should be functional however it's not manufactured yet for a physical, hands-on testing.

## Description

This is my first fully independent KiCad project after following the tutorial for the STM32F103.
A STM32F411 Discovery board was something I wanted to buy since a long time.
However, I figured out it's better if I learn to make myself something similar and have it assembled.<br>
<br>
Due to component density and pin count, this schematic ended up being a 6-layer board. <br>
<br>
Layer parameters and component choice has been made considering jlcpcb constraints and components library(for the sake of orientation). It can be manufactured by ANY service. <br>
Also feel free to change constraints / components. <br>
<br>
<br>


## Differences between this and actual Discovery Boards.

* Due to unavailability of components, I removed all the audio subsystem that Discovery boards have and replaced it with extra pins

* Again due to components availability some components have been replaced with others and / or similar components

* I have no idea how many layers Discovery Kits actually have, this one has 6 layers: Signal(F)/GND/Signal/Signal/Power/Signal(B)

## Installation
1. Create a project called "STM32 Discovery" in KiCad 7.0 (while this is NOT a Discovery kit the name persists from when I first created the project for orientation)

2. Copy all files <except for those in the (previous_sections_files)> from this Git inside the .../Documents/KiCad/7.0/projects/STM32 Discovery

3. Go to the folder "(previous_sections_files)" you will see two subfolders "3dmodels" and "footprints". Copy those in "/Documents/KiCad/7.0/3dmodels" and ""/Documents/KiCad/7.0/footprints" respectively

## Screenshoots

![image](https://user-images.githubusercontent.com/123891760/231435566-b099c66b-cb10-4f03-ba53-ea7f8dd1ff47.png)
![image](https://user-images.githubusercontent.com/123891760/231435576-f2bf39a7-243d-45bf-89fb-1a85f6d80f61.png)
![image](https://user-images.githubusercontent.com/123891760/231435582-d1af9ebd-3e53-462f-b5fa-1795a2eff58a.png)
![image](https://user-images.githubusercontent.com/123891760/231435599-b868741a-96a5-4103-b813-e05f28d94553.png)
