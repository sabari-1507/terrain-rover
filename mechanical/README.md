# Mechanical Design – Terrain Rover

## Overview

This directory contains the mechanical CAD design and assembly documentation for the Terrain Rover. The mechanical system includes the chassis, double-rocker mobility mechanism, wheel assemblies, and custom 3D-printed tyres.

## Mechanical Design

### 1. Rover Chassis
The rover structure incorporates acrylic sheets, sheet metal components, and stainless-steel (SS) tubes for structural support, mounting, and mechanical integration.

### 2. Double-Rocker Mechanism
A double-rocker mechanism is used in the rover's mobility system to support wheel articulation over uneven terrain.

### 3. Custom 3D-Printed Tyres
The tyres use a dual-material construction:

- **Outer tyre:** TPU 95A for a flexible, durable tyre surface.
- **Inner rim:** PETG for the rigid supporting structure.

This configuration combines the flexibility of TPU with the structural rigidity of PETG.

## CAD Visualisation

### Rover Assembly

**Isometric View**

![Rover Isometric View](images/Rover_iso.png)

**Front View**

![Rover Front View](images/Rover_front.png)

**Rear View**

![Rover Rear View](images/Rover_back.png)

**Side View**

![Rover Side View](images/Rover_left.png)

**Bottom View**

![Rover Bottom View](images/Rover_bottom.png)

### Custom Tyre Design

**Isometric View**

![Tyre Isometric View](images/Tyre_iso.png)

**Front View**

![Tyre Front View](images/Tyre_Front.png)

**Side View**

![Tyre Side View](images/Tyre_side.png)

**Cross-Sectional View**

![Tyre Cross-Sectional View](images/Tyre_cross_Section.png)

## Materials and Manufacturing

| Component | Material / Process |
|---|---|
| Outer tyre | TPU 95A – 3D printed |
| Inner tyre rim | PETG – 3D printed |
| Structural members | Stainless-steel (SS) tubes |
| Panels and mounting components | Acrylic sheets and sheet metal |

## Directory Structure

```text
mechanical/
├── README.md
├── images/
│   ├── Rover_iso.png
│   ├── Rover_front.png
│   ├── Rover_back.png
│   ├── Rover_left.png
│   ├── Rover_bottom.png
│   ├── Tyre_iso.png
│   ├── Tyre_Front.png
│   ├── Tyre_side.png
│   └── Tyre_cross_Section.png
├── cad/
└── drawings/
```

`cad/` and `drawings/` can contain the corresponding CAD models, assemblies, and engineering drawings when available.
