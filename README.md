# Awesome BESS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome open-source software, standards, frameworks, and resources for **Battery Energy Storage Systems (BESS)**.

Battery Energy Storage Systems (BESS) are essential for modern grids to manage renewable energy intermittency, support frequency and voltage regulation, and optimize electricity costs. This curated list compiles resources to help engineers and developers build, simulate, and operate grid-scale battery storage.

---

## Contents

- [Standards & Regulations](#standards--regulations)
- [Edge Gateways & SCADA](#edge-gateways--scada)
- [Simulation & Battery Models](#simulation--battery-models)
- [Power System Analysis](#power-system-analysis)
- [Protocols & Communication](#protocols--communication)
- [Research Papers](#research-papers)

---

## Standards & Regulations

- **[IEC 62443](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series)** - Security for industrial automation and control systems (IACS).
- **[IEEE 1547](https://standards.ieee.org/ieee/1547/6932/)** - Standard for Interconnection and Interoperability of Distributed Energy Resources.
- **[NTSyCS (Chile)](https://www.cne.cl/)** - Chilean Grid Operator (CNE) Technical Standard for System Security and Quality of Service (droop control, ramp limits, telemetry).
- **[IEEE 2030.5](https://standards.ieee.org/ieee/2030.5/5895/)** - Smart Energy Profile Application Protocol.
- **[SunSpec](https://sunspec.org/)** - Modbus standards for solar PV and energy storage devices.

---

## Edge Gateways & SCADA

- **[open-bess-edge](https://github.com/bess-solutions/open-bess-edge)** - Industrial edge gateway and controller implementing droop PFR, active/reactive ramping controls, and IEC 62443 cybersecurity guidelines.
- **[Fledge](https://fledge-iot.github.io/)** - Open-source industrial IoT gateway framework for manufacturing and energy grids.
- **[OpenSCADA](https://github.com/OpenSCADA/OpenSCADA)** - A robust open-source SCADA system built on Java and Eclipse technology.

---

## Simulation & Battery Models

- **[PyBaMM](https://www.pybamm.org/)** - Python Battery Mathematical Modelling. Solves physics-based DFN/SPM models for LFP/NMC cell degradation.
- **[SimSES](https://github.com/TUM-EEN/SimSES)** - Simulation of Stationary Energy Storage Systems. Focuses on degradation-informed economic dispatch.
- **[bess-optimizer](https://github.com/bess-solutions/bessai-pilot)** - MILP-based dispatch optimizer for intraday arbitrage and secondary reserves.

---

## Power System Analysis

- **[PyPSA](https://pypsa.org/)** - Python for Power System Analysis. Operates unit commitment, transmission flow, and dispatch simulations.
- **[pandapower](https://www.pandapower.org/)** - An easy-to-use network calculation program for power flow, optimal power flow, and contingency analysis.

---

## Protocols & Communication

- **[PyModbus](https://github.com/pymodbus-dev/pymodbus)** - A full Modbus protocol implementation in Python supporting TCP, RTU, and ASCII.
- **[pydnp3](https://github.com/georgekarpenkov/pydnp3)** - Python bindings for the DNP3 (Distributed Network Protocol) stack.
- **[scapy](https://scapy.net/)** - Powerful interactive packet manipulation program, excellent for auditing OT network protocols.

---

## Research Papers

- **[LCOS Quantification](https://doi.org/10.1016/j.est.2020.101600)** - *Levelized Cost of Storage (LCOS) for battery technologies: A comprehensive review.*
- **[Degradation Modelling](https://doi.org/10.1016/j.jpowsour.2018.04.103)** - *A review of battery degradation mechanisms and diagnostic methods for grid-scale systems.*

---
*Contributions are welcome! Read the [Contributing Guidelines](https://github.com/bess-solutions/awesome-bess/blob/main/CONTRIBUTING.md) to add resources.*
