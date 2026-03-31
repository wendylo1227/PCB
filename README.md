# PCB
# Analog PCB System

Designed and fabricated an analog PCB system integrating power conversion, voltage regulation, and signal amplification, with oscilloscope-based verification.

---

## Overview

This project implements a complete analog system on a PCB, including:

- Voltage quadrupler (AC to DC conversion)
- Low Dropout Regulator (LDO) for stable DC output
- Common-source amplifier for signal amplification

The system demonstrates an end-to-end signal chain from AC input to amplified output.

---

## System Architecture

The system consists of three main stages:

1. **Voltage Quadrupler**  
   Converts AC input into higher DC voltage  

2. **LDO Regulator**  
   Stabilizes the DC output to a constant voltage  

3. **Common-Source Amplifier**  
   Amplifies the input AC signal  

---

## PCB Design

![PCB Layout](images/pcb_layout.png)

- Designed PCB layout using PADS
- Completed routing, component placement, and grounding  
- Integrated multiple analog circuits into a single board  

---

## PCB Fabrication

![PCB Bottom](images/pcb_bottom.jpg)

Fabrication process:

- UV exposure (~60 seconds)  
- Development  
- Etching  
- Drilling and alignment  
- Soldering components  

---

## Hardware Implementation

![PCB Top](images/pcb_top.jpg)

- Assembled all components on the fabricated PCB  
- Verified circuit connectivity and functionality  

---

## Measurement Setup

![Measurement Setup](images/measurement.jpg)

- Used oscilloscope probes to measure output signals  
- Tested each stage of the system individually  

---

## Measurement Results and Verification

![Oscilloscope](images/oscilloscope.jpg)

- **CH1 (Vout1): 15.7 V** → Voltage quadrupler operates correctly  
- **CH2 (Vout2): 5.97 V** → LDO provides stable ~6V output  
- **CH3 (Vout3): 140 mVpp** → Amplifier produces valid AC signal  

### System Verification

The system successfully achieves:

- AC to DC voltage boosting  
- Stable voltage regulation  
- Functional signal amplification  

---

## Key Learnings

- Analog circuit design and integration  
- PCB layout and fabrication process  
- Power conversion and regulation  
- Signal amplification using MOSFET  
- Oscilloscope-based debugging and verification  

---

## Technologies

- Analog Circuit Design  
- PCB Design & Fabrication  
- Oscilloscope Measurement  
- Power Electronics  
- Amplifier Design  

---
