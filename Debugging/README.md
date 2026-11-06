# Table of Contents

- [Mosfets](#mosfets) 
- [RJ45 Ethernet Ports](#rj45-ethernet-ports) 
- [WavTrigger](#wavtrigger)



# Mosfets

**Debugging Reverse Voltage Protection P-Channel and N-Channel MOSFETs**

<img src = "/Debugging/ref-images/MOSFETS.png" width="500" alt="MOSFETS diagram"> <img src = "/Debugging/ref-images/N-MOSFET.png" width="500" alt="MOSFETS diagram">

*Note that two different MOSFET form factors are displayed above.*

## General MOSFET Testing

Use `Continuity` and `Voltage` multimeter settings to test a P-Channel or N-Channel MOSFET. Set one test point as reference (negative probe on source), and measure to the other pins.

| # | Measurement points | Healthy reading | Faulty reading (meaning) |
|---|---|---|---|
| 1 | **Drain to Source** | Open (OL) one way. 0.4–0.7 V the other way in diode mode (body diode present). | ~0 Ω both ways: MOSFET has shorted or has a solder bridge. |
| 2 | **Gate to Source** | Open or very high (OL) both ways. | Near 0 Ω: gate shorted to source or ground. |
| 3 | **Gate bias resistor** (if present) | Continuity depends on circuit design (check schematic). | Open: resistor or trace broken. ~0 Ω when not expected: resistor bridged or shorted. |
| 4 | **Drain to ground** | Depends on circuit topology (open if drain is floating). | ~0 Ω when not expected: drain permanently pulled to ground (load always on). |
| 5 | **Drain to load connection** | ~0 Ω (should be a direct trace/wire). | Open: broken trace, cold solder joint, or corroded connection. |
| 6 | **Gate pull-down/pull-up** | Depends on circuit design. Check for expected pull-down or pull-up resistor to bias gate. | ~0 Ω unexpectedly: gate stuck at bias rail. |

**Key points:**
- Always test in **diode mode** on the multimeter for accurate body diode readings
- Compare results to the circuit schematic to verify expected topology
- A shorted drain-to-source in both directions indicates component failure
- Gate-to-source should always be isolated; any continuity indicates a problem

# RJ45 Ethernet Ports

**Pinout for RJ45 through-hole Ethernet Ports**

<img src = "/Debugging/ref-images/RJ45-ETHERNET.png" width="650" alt="MOSFETS diagram">

# WavTrigger

- *Is RX to TX and TX to RX?*
