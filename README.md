# CNCU-01 4-Layer PCB Redesign

![PCB 3D](docs/PCB_3D.png)

## Overview

* This project is a PCB redesign of the open-source CNCU-01 controller board.

* The original design was implemented as a 2-layer PCB. In this project, the board was migrated to a 4-layer stackup to improve routing quality, power integrity, and manufacturability.

## Layer Stackup

![Layer Stackup](docs/PCB_STACKUP.png)

## Differential Pair Calculation (SI9000)
Differential impedance: 100Ω

![Layer Stackup](docs/SI9000_D100.png)
Differential impedance: 90Ω

![Layer Stackup](docs/SI9000_D90.png)
Single-ended impedance: 50Ω

![Layer Stackup](docs/SI9000_S50.png)

## My Contributions

* Migrated the original PCB from 2 layers to 4 layers
* Defined a new PCB stackup
* Calculated controlled impedance traces using SI9000
* Configured differential pair routing rules
* Optimized power and ground planes

## Tools

- Altium Designer
- SI9000

## Reference

Original project:
https://github.com/MikhailBerezhanov/CNCU-01
