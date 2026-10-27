# Custom Aluminum Electronic Enclosure

<img width="1215" height="916" alt="3d_render" src="https://github.com/user-attachments/assets/7bf756ae-3ec5-4434-8bf6-35c4cb046ca6" />


## 📌 Project Overview
This repository contains the complete engineering drawing and flat-pattern design for a custom sheet-metal electronic enclosure. Fabricated from Aluminum 5052-H32, this lightweight and corrosion-resistant housing is designed for flat-pattern manufacturing (laser cutting and press-brake bending). It features a complex 13-bend geometry to create a rigid, enclosed chassis with custom I/O access.

## 📊 Key Specifications
| Parameter | Specification |
| :--- | :--- |
| **Part Type** | 5-Sided Sheet Metal Enclosure (Open Top) |
| **Material** | Aluminum 5052-H32 (1.5 mm thickness) |
| **Overall Size** | Approx. 132.20 mm × 100.00 mm |
| **Manufacturing Process** | Laser Cutting → Bending → Hardware Insertion |
| **Hardware** | 4 × Corner PEM Nut Cutouts, 8 × Internal PCB Mounts (M4/M5) |
| **Bends** | 13 × 90° Downward Bends (per bend table A–M, 2.00 mm Inner Radius) |

## 🛠️ Features
*   **Complex Corner Geometry:** The four corners feature specialized fold-down tabs with square cutouts designed for press-fit hardware (PEM nuts), allowing for a secure lid attachment.
*   **Side Access Cutouts:** Large, rounded-rectangular cutouts on the side panels (88.00 mm and 50.00 mm widths) to provide access for cable routing, connectors, and ventilation.
*   **Internal Mounting Grid:** The base plate features multiple pre-drilled holes, including a 4× Ø5.00 mm pattern and an 8× Ø4.00 mm pattern, to accommodate various internal PCBs and component standoffs.
*   **Precision Flat Pattern:** Engineered with exact bend allowances and corner reliefs to prevent material tearing during the 13-step bending process.
*   **Cost Efficient:** 5052-H32 aluminum for the enclosure body. It is the lowest-risk, lowest-total-cost material for a laser-cut, 12-bend, PEM-inserted sheet-metal enclosure.

<img width="1133" height="1069" alt="Flat" src="https://github.com/user-attachments/assets/3136246a-2aa2-4ba1-9fbc-641780d40d44" />



## 📂 Repository Structure
*   `/cad` - 3D models (SolidWorks files).
*   `/drawings` - 2D flat patterns, DXF files for laser cutting, and PDF engineering drawings.
*   `/images` - Renders and reference photos.


## 🚀 Getting Started
1. Review the `drawings/flat_pattern.dxf` file for laser cutting and CNC punching.
2. Refer to the `Aluminum_Enclosure_Specification.pdf` for the formal bend table (13 bends, all 90° DOWN with a 2 mm inner radius) and precise hole locations.
3. Follow the fabrication process: laser cut the flat pattern, apply the 13 bends using a press brake, and insert the corner hardware.
