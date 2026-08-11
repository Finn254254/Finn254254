# Hi, I'm Finn

I am a hardware designer building **ORCA Servers**: a modular local-compute and server hardware platform built around custom PCBs.

## ORCA Hardware Platform

**[Explore the ORCA Hardware Platform →](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/hardware-platform.md)**

The platform is being developed as separate, reusable hardware modules rather than one large motherboard:

```text
Compute ─┐
Compute ─┼─ Backplane ─ I/O
Storage ─┤      │
Fabric  ─┘   Control
              │
            Power
```

The roadmap currently includes Compute Modules, I/O, Power, Control, Backplane, Network/Fabric, Storage and future accelerator hardware.

## Ongoing ORCA projects

### [ORCA PCIe NVMe Link V3.0](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-)

Custom PCIe x4 to M.2 NVMe expansion board. This is an early ORCA storage-development project and practical test of PCIe routing, M.2 and PCB edge connections.

Status: design complete enough to prepare for prototyping and physical testing.

### [ORCA Compute Module](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/compute.md)

Replaceable processing module concept containing the SoC, RAM, PMIC, boot storage and processor-specific power hardware.

Status: architecture / concept.

### [ORCA Control](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/control.md)

Dedicated management board for power control, reset, fan management, temperatures, watchdogs and communication with compute nodes.

Status: V3s-based design direction under development.

### [ORCA Power](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/power.md)

Server-level power input, protection, distribution, switching and monitoring while processor-specific rails remain local to Compute Modules.

Status: concept / planned.

### [ORCA I/O](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/io.md)

Carrier-style connectivity board for USB, Ethernet, GPIO, debug and expansion interfaces.

Status: concept / planned.

### [ORCA Backplane](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/backplane.md)

Common physical backbone intended to connect Compute, Power, Control, Storage and networking modules.

Status: concept / interface planning.

### [ORCA Network / Fabric](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/network-fabric.md)

Internal node networking with a progression from conventional Ethernet toward higher-bandwidth links for distributed compute.

Status: concept / planned.

### [ORCA Storage](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/boards/storage.md)

Future modular NVMe and bulk-storage hardware building on the PCIe NVMe Link work.

Status: early development / concept.

## Current milestone

```text
ORCA PCIe NVMe Link
├── Schematic        complete
├── PCB layout       complete
├── 3D review        complete
├── Manufacturing    preparing
└── Physical testing pending

ORCA Platform
├── Architecture     documenting
├── Control          developing
├── Compute          planning
├── Power            planning
├── I/O              planning
├── Backplane        planning
├── Fabric           planning
└── Storage          developing
```

## Support ORCA development

ORCA is currently self-funded. Support goes toward prototype PCB fabrication, components, assembly, engineering review and hardware testing.

**[Support ORCA on Buy Me a Coffee](https://buymeacoffee.com/finnmather)**

Contributions are voluntary support for development. They are not pre-orders, investments or promises of finished hardware.

## Follow the work

- [ORCA Hardware Platform](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-/blob/main/docs/hardware-platform.md)
- [ORCA PCIe NVMe Link](https://github.com/Finn254254/ORCA-PCIe-NVMe-Link-)

I am documenting ORCA as it develops, including board concepts, design decisions, prototypes and test results.
