# My Homelab

A compact 10-inch 8U desktop homelab housing a 4-node Dell OptiPlex micro compute cluster, live hardware telemetry display, managed VLAN network stack, and containerized routing.

## Hardware Specifications
- **Compute Cluster:** 4x Dell OptiPlex Micro PCs (3x OptiPlex 3040, 1x OptiPlex 3050)
- **Hypervisor:** Proxmox VE 8.x Cluster
- **Rack Frame:** DeskPi RackMate T1 10-Inch 8U Aluminum Chassis
- **Network Switch:** TP-Link TL-SG108PE 8-Port Gigabit Switch (802.1Q VLANs, 4x PoE)
- **Telemetry Display:** 7-Inch Waveshare HDMI IPS LCD (1024x600) driving `btop` on OptiPlex 3050
- **Power Distribution:** VEVOR 1U 8-Outlet PDU + CyberPower UPS

## 8U Rack Allocation

| Unit | Component | Description / Mounting |
| :---: | :--- | :--- |
| **U8** | 7" LCD Telemetry Display | 2U Panel (MakerWorld 1111939) |
| **U7** | Telemetry Panel Extension | (Spans U7–U8) |
| **U6** | Keystone Patch Panel | Yankok 12-Port Blank + Cat6 Couplers |
| **U5** | Network Switch | TP-Link TL-SG108PE 8-Port PoE Switch |
| **U4** | Compute Node #2 | Dell OptiPlex 3040 (1U PETG Mount) |
| **U3** | Compute Node #1 | Dell OptiPlex 3040 (1U PETG Mount) |
| **U2** | Compute Node #3 | Dell OptiPlex 3040 (1U PETG Mount) |
| **U1** | Head Node | Dell OptiPlex 3050 (1U PETG Mount) |

## 3D Printing Parameters (Bambu Lab PEI Plate)
- **Filament:** Polymaker / SUNLU / Bambu Lab PETG
- **Nozzle / Bed Temp:** 245°C / 75°C
- **Wall Loops:** 4 Perimeters
- **Infill:** 25% Gyroid
- **Support:** Tree (Auto) – Build Plate Only
