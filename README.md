# 20V-5V Buck Converter

## Overview
Goal: fully functioning buck converter that can step down voltage from 20V to 5V with less than 5% ripple. Custom PCB designed with KiCad, assembled with capacitors, inductors, gate driver, MOSFETs, and Op-Amp.

## Key Results
- Peak efficiency: ~85% driving 5W load
- Output ripple: <40mV

## Design
- **Topology:** Asynchronous Buck
- **Duty Cycle:** 0.25 to step down voltage by x4
- **PCB:** 2-layer, component selection to trade off between size and efficiency

## What I'd Change
This was my first real power converter design, which helped me practice circuit design, component selection, and understanding power converters. If I could redo this project, I would definitely use a 4 layer board to optimize my layout a lot and cut down on parasitics from excess loop length. I would also simulate my system first in PLECS or SPICE adjacent software to gain a better understanding of what specs I am targeting and how to achieve them.

## Media
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ba89d1b3-17cd-4a29-ad20-30a93c0bad51" />


## Tools
LTSpice, KiCAD, Oscilloscope
