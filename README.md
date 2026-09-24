# Yagi Antenna

## Overview

The Yagi antenna is a directional end-fire antenna designed and simulated using CST Studio Suite.

This project focuses on the design and simulation of a Yagi antenna operating at **1 GHz**. The antenna uses electromagnetic coupling between a driven element and parasitic elements to achieve directional radiation.

## Working Principle

A Yagi antenna consists of:

- **Driven Element** – The central dipole connected to the RF source.
- **Reflector** – A slightly longer parasitic element placed behind the driven element.
- **Directors** – Shorter parasitic elements placed in front of the driven element.

The parasitic elements are not electrically connected to the source. They interact with the driven element through electromagnetic coupling.

The reflector helps reduce radiation toward the rear, while the directors help reinforce radiation in the forward direction. This produces a directional end-fire radiation pattern.

## Design and Simulation

The antenna was designed and simulated using **CST Studio Suite**.

### Design Parameters

| Parameter | Value |
|---|---:|
| Operating Frequency | 1 GHz |
| S11 / Return Loss | -18.29 dB |
| VSWR | 1.27 |
| Gain | 8.049 dBi |
| Directivity | 8.029 dBi |

## Simulation Results

### Antenna Model

The CST simulation model of the Yagi antenna is shown below.

![Yagi Antenna Model](Simulation_Results/Antenna_Model.jpeg)

### S11 / Return Loss

The S11 parameter shows the amount of power reflected from the antenna input.

![S11 Return Loss](Simulation_Results/S11_Return_Loss.png)

### VSWR

VSWR indicates the impedance matching between the antenna and the feeding system.

![VSWR](Simulation_Results/VSWR.png)

### Gain

The simulated antenna gain is **8.049 dBi**.

![Gain](Simulation_Results/Gain.png)

### Directivity

The simulated antenna directivity is **8.029 dBi**.

![Directivity](Simulation_Results/Directivity.png)

### Radiation Pattern

The radiation pattern demonstrates the directional radiation characteristics of the Yagi antenna.

![Radiation Pattern](Simulation_Results/Radiation_Pattern.png)

## Key Results

The simulated Yagi antenna operates at **1 GHz** and provides:

- S11 of **-18.29 dB**
- VSWR of **1.27**
- Gain of **8.049 dBi**
- Directivity of **8.029 dBi**

These results demonstrate the directional characteristics and impedance matching performance of the simulated antenna.

## Software Used

- CST Studio Suite

## Project Type

**Antenna Design and Simulation**
