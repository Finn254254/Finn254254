<div align="center">

# Finn Mather

### Building ORCA — custom computers from schematic to Linux

I design PCBs, embedded systems, and modular server hardware in Norfolk, UK.

[![Orca One](https://img.shields.io/badge/FLAGSHIP-Orca_One_V1.0-111111?style=for-the-badge)](https://github.com/Finn254254/orca-one)
[![PCIe NVMe Link](https://img.shields.io/badge/STORAGE-PCIe_NVMe_Link-005f73?style=for-the-badge)](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-)
[![ORCA OS](https://img.shields.io/badge/SOFTWARE-ORCA_OS-1f6feb?style=for-the-badge)](https://github.com/Finn254254/orca-os)

</div>

## Featured ORCA PCB hardware

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/Finn254254/orca-one">
        <img src="https://raw.githubusercontent.com/Finn254254/orca-one/main/images/orca-one-front.png" alt="Orca One V1.0 front render">
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-">
        <img src="https://raw.githubusercontent.com/Finn254254/ORCA-PCIe-NVMe-Link-/main/images/pcb-render-front.png" alt="ORCA PCIe NVMe Link V3.0 front render">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong><a href="https://github.com/Finn254254/orca-one">Orca One V1.0</a></strong><br>
      Custom Allwinner V3s Linux SBC
    </td>
    <td align="center">
      <strong><a href="https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-">ORCA PCIe NVMe Link V3.0</a></strong><br>
      Custom PCIe x4 to M.2 NVMe expansion board
    </td>
  </tr>
</table>

## Orca One V1.0

Orca One is my custom Linux single-board computer built around the **Allwinner V3s**. I designed the schematic, four-layer PCB, power system, external interfaces, and manufacturing package from scratch as the first complete board in the ORCA hardware platform.

| | |
| --- | --- |
| **Processor** | Allwinner V3s ARM SoC |
| **Board** | Custom four-layer PCB designed in KiCad 9 |
| **Connectivity** | Ethernet, USB-A 2.0, MicroSD, UART, GPIO, and fan control |
| **Power** | USB-C input with onboard 3.3 V, 3.0 V, 1.8 V, 1.2 V, and 1.1 V rails |
| **Current stage** | Design complete; preparing for fabrication and bring-up |

**[Explore the complete Orca One project →](https://github.com/Finn254254/orca-one)**

## ORCA PCIe NVMe Link V3.0

The PCIe NVMe Link is a compact storage-expansion board that connects an M.2 NVMe drive through a custom PCIe x4 edge interface. It is an early ORCA storage module and a practical test platform for PCIe routing, M.2 connectivity, and modular expansion.

| | |
| --- | --- |
| **Host interface** | PCIe x4 PCB edge connector |
| **Storage** | M.2 M-key NVMe socket |
| **Design** | Custom schematic and PCB layout |
| **Current stage** | Design and 3D review complete; preparing for prototyping |

**[Explore the ORCA PCIe NVMe Link project →](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-)**

## The ORCA platform

ORCA is a growing family of custom computing hardware designed as interoperable modules rather than one fixed motherboard.

```text
Compute ─┐
Compute ─┼── Backplane ─── I/O
Storage ─┤       │
Fabric  ─┘    Control
                │
              Power
```

| Project | Purpose | Stage |
| --- | --- | --- |
| **[Orca One](https://github.com/Finn254254/orca-one)** | Complete V3s Linux SBC and hardware bring-up platform | Preparing for fabrication |
| **[ORCA PCIe NVMe Link](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-)** | PCIe x4 to M.2 NVMe storage expansion board | Design and 3D review complete |
| **[ORCA OS](https://github.com/Finn254254/orca-os)** | Linux software and board-support work for ORCA hardware | Early development |
| **ORCA modular server** | Compute, control, power, I/O, backplane, fabric, and storage architecture | Architecture and prototyping |

## What I work on

- Schematic capture and PCB layout
- Power distribution and multi-rail board design
- High-speed storage and interconnect hardware
- Embedded Linux board support and bring-up
- Modular compute and server architecture
- Manufacturing outputs, BOM preparation, and prototype testing

## Current roadmap

```text
Orca One
├── Schematic and PCB       complete
├── Manufacturing package  complete
├── Prototype fabrication  next
├── Assembly and power-up   pending
├── Linux boot              pending
└── Interface validation    pending
```

## Follow and support the build

I document ORCA as it develops—from design decisions and PCB revisions to fabrication, assembly, and Linux bring-up.

- **[Browse the ORCA repositories](https://github.com/Finn254254?tab=repositories&q=orca)**
- **[Visit my project portfolio](https://finn254254.github.io)**
- **[Support prototype development](https://buymeacoffee.com/finnmather)**

Support is voluntary and goes toward PCB fabrication, components, assembly, engineering review, and hardware testing. It is not a pre-order or investment.

---

<sub>ORCA design files are made public for project review and funding requirements. Individual repositories state their applicable licensing terms; Orca One is proprietary and all rights are reserved.</sub>
