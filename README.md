# OMSI Electronics Team Methods & Practices

**Documentation hub for electronics assembly, troubleshooting, and digital fabrication procedures used at the Oregon Museum of Science and Industry (OMSI).**

## Table of Contents

- [1. Install Practices](#install-practices)
  - [1.1 Connections](#connections)
    - [JST Connectors](#jst-connectors)
    - [Phoenix Connectors](#phoenix-connectors)
    - [Onboard Microcontroller Mounting](#onboard-microcontroller-mounting)
    - [Amplifier & Speaker Connections](#amplifier--speaker-connections)
    - [Power Supplies](#power-supplies)
  - [1.2 Buttons](#buttons)
- [2. Debugging](#debugging)
  - [2.1 MOSFETs](#mosfets)
  - [2.2 RJ45 Ethernet Ports](#rj45-ethernet-ports)
  - [2.3 WavTrigger](#wavtrigger)
- [3. Digital Fabrication](#digital-fabrication)
  - [3.1 Laser Cutting](#laser-cutting)
  - [3.2 3D Printing](#3d-printing)
- [4. Quick Reference Guides](#quick-reference-guides)
- [5. Safety & Best Practices](#safety--best-practices)
- [6. Component Library](#component-library)
- [7. Project Templates](#project-templates)

---

## Install Practices

Installation and assembly guidelines for core electronics components and systems.

### Connections

Detailed procedures for connecting common components used in exhibits and systems.

- [JST Connectors](./install-practices/connections/)
- [Phoenix Connectors](./install-practices/connections/)
- [Onboard Microcontroller Mounting](./install-practices/connections/)
- [Amplifier & Speaker Connections](./install-practices/connections/)
- [Power Supplies](./install-practices/connections/)

### Buttons

Button installation and configuration procedures.

- [Buttons Best Practices](./install-practices/buttons/)

---

## Debugging

Troubleshooting guides and reference materials for common components and systems.

- [MOSFETs: Reverse Voltage Protection Diagnostics](./Debugging/README.md#mosfets)
- [RJ45 Ethernet Port Pinouts](./Debugging/README.md#rj45-ethernet-ports)
- [WavTrigger Troubleshooting](./Debugging/README.md#wavtrigger)

---

## Digital Fabrication

Procedures for fabricating custom parts and enclosures.

### Laser Cutting

Workflow and best practices for the Epilog Laser Fusion M2.

- [Startup Guide & Focusing](./digital-fabrication/laser-cutting/)
- Equipment: Epilog Laser Fusion M2, Inkscape v1.4.2, Dashboard 2.2.18.0

### 3D Printing

Optimization and material guidance for FDM printing with the Elegoo system.

- [3D Printing Practices](./digital-fabrication/3d-printing/)
- Calibrated for Cura with Elegoo filaments

---

## Quick Reference Guides

*(Suggested additions)*

Consider creating concise one-page guides for:
- **Pinout Diagrams** - Common connectors and microcontroller pinouts
- **Soldering Checklist** - Do's and don'ts for reliable joints
- **Multimeter Testing Matrix** - Common measurements and expected ranges
- **Cable Management** - Best practices for durability and troubleshooting

---

## Safety & Best Practices

*(Suggested additions)*

Important for a museum environment with volunteers and visitors:
- **Electrical Safety** - ESD precautions, voltage hazards, live circuit handling
- **Tool Safety** - Soldering iron, hot glue, laser cutter, 3D printer safety
- **Material Safety** - Filament types, solder fumes, laser-safe materials
- **Testing Procedures** - How to validate repairs before re-deployment
- **Incident Documentation** - Log for failures and root causes

---

## Component Library

*(Suggested additions)*

Centralized reference for commonly used components:
- **Microcontrollers** - Teensy 3.x/4.x pinouts and capabilities
- **MOSFETs** - Part numbers, ratings, and application guidelines
- **Connectors** - JST, Phoenix, 3.5mm, RJ45 specifications and wiring
- **Power Components** - Voltage regulators, power supplies, fuses
- **Sensors** - Motion, temperature, light, audio components used
- **Passive Components** - Resistor color codes, capacitor ratings

---

## Project Templates

*(Suggested additions)*

Standardized documents to streamline new exhibit development:
- **Exhibit Specification Template** - Electrical requirements checklist
- **Wiring Diagram Template** - Standard symbols and layout conventions
- **Assembly Work Instruction** - Step-by-step assembly procedure format
- **Test & Validation Checklist** - Acceptance criteria before deployment
- **Maintenance Log Template** - Track component lifecycles and failures
