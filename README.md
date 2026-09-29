# My HackPad Keyboard

A keyboard that can type an absurdly large amount of characters in a short space.
By combining the 16 keys with the knob, each turn of the knob makes each key type a different thing. This way, you can go from your normal A B C's to weird hieroglyphics.

# Features/Things used:

- 3d printed case (bottom section with a usb c hole wita top cover with a knob and key hole(s))
- 99.5 x99.5 mm pcb with a 4x4 matrix of buttons on it (+ knob)
- 16 LED's for each of buttons (cool lighting effects)

<img src=assets/keyboardnotop.png alt="Top View" width="250"/>
<img src=assets/caseonly.png alt="Caseonly" width="250"/>

# CAD
Used fusion 360
Pretty easy. Bottom case with usb c hole + top case with key, knob, and LED holes.

<img src=assets/keyboardwhole.png alt="CAD" width="250"/>
<img src=assets/keyboard.png alt="CAD" width="250"/>

# PCB

PCB pics attached below.
Kicad used

<img src=assets/schematic.png alt="Schematic" width="250"/>
Schematic
<img src=assets/pcb.png alt="PCB" width="250"/>
PCB
CAD render:
<img src=assets/pcbonlyrender.png alt="Schematic" width="250"/>

# Firmware:
Python with a main.py used.

#How the final product should look:

<img src=assets/main.png alt="Code" width="500"/>
Main.py

# BOM

Everything that is needed to make this:

- 1x custom pcb
- 1x Rotary encoder
- 1x Seeed XIAO RP2040
- 16x SK6812MINI-E RGB LEDs
- 16x DSA keycaps
- 16x 1N4148 Diodes
<img src=assets/bom.png alt="stuffused" width="500"/>
