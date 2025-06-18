## 🔧 Project Overview

This project focuses on the **steady-state thermal analysis** of a **ventilated grey cast iron disc brake** using ANSYS 2025 R1. The primary objective is to simulate how the brake disc dissipates heat through conduction, radiation, and convection under realistic boundary conditions during braking.

###  CAD Model Specifications (from SOLIDWORKS)

- **Model Name:** Ventilated Disc Brake
- **Software Used:** SOLIDWORKS (for modeling), ANSYS (for simulation)
- **Mass:** 80 grams (0.08 kg)
- **Volume:** 80,000.66 mm³
- **Surface Area:** 38,189.20 mm² (0.0382 m²)
- **Disc Shape:** Circular with central and radial ventilation holes
- **Outer Diameter:** 150 mm
- **Inner Diameter:** 20 mm
- **Material:** Grey Cast Iron


###  Simulation Environment (ANSYS)

- **Analysis Type:** Steady-State Thermal
- **Boundary Conditions:**
  - **Temperature (fixed):** 50°C on front, back, and edge faces
  - **Radiation:** Emissivity = 1.0, Ambient Temp = 30°C
  - **Convection:** h = 25 W/m²·K on inner hole surfaces, Ambient Temp = 30°C


---
