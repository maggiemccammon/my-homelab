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
+-------------------------------------------------------+
| U7–U8 (Top): 7" LCD Telemetry Panel (MakerWorld 1111939)|
| U6: Yankok 12-Port Blank Keystone Patch Panel         |
| U5: TP-Link TL-SG108PE 8-Port Switch                  |
| U3–U4: OptiPlex 3040 Nodes #1 & #2 (1U PETG Brackets) |
| U1–U2 (Bottom): OptiPlex 3040 #3 & 3050 Head Node     |
+-------------------------------------------------------+
## 3D Printing Parameters (Bambu Lab PEI Plate)
- **Filament:** Polymaker / SUNLU / Bambu Lab PETG
- **Nozzle / Bed Temp:** 245°C / 75°C
- **Wall Loops:** 4 Perimeters
- **Infill:** 25% Gyroid
- **Support:** Tree (Auto) – Build Plate Only
