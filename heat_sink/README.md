#  Heat Sink Thermal Analysis

This project presents a comparative thermal analysis of a heat sink conducted using ANSYS Workbench. The main objective is to evaluate the heat dissipation performance under two distinct thermal loading conditions and to observe how the method of heat application affects the maximum temperature and temperature distribution.

##  Objective
To compare thermal behavior of the heat sink in:
1. **Case 1:** Uniform heat flux applied over the entire base surface.
2. **Case 2:** Localized heat flux applied to eight discrete components simulating electronic devices.

##  Heat Sink Specifications
- **Dimensions:** 100 mm × 50 mm × 20 mm
- **Material Tested:** Aluminium and Copper
- **Heat Input:** 144 W total
  - **Case 1:** 144 W uniformly applied
  - **Case 2:** 18 W per component × 8 components
- **Cooling Condition:** Natural convection on all non-heated surfaces
- **Heat Transfer Coefficient:** 20 W/m²·K
- **Ambient Temperature:** 25°C

##  Simulation Setup
- CAD geometry imported into ANSYS Mechanical
- Material properties applied
- Fine meshing used for accurate thermal gradients
- Steady-state thermal analysis solver used

##  Results Summary

| Material    | Max Temp (Uniform) | Max Temp (Localized) |
|-------------|--------------------|------------------------|
| Aluminium   | 85.67°C            | 177.08°C               |
| Copper      | 84.65°C            | 174.32°C               |

### Key Insights:
- **Localized heating (Case 2)** resulted in significantly higher temperatures due to poor thermal spreading.
- **Uniform heating (Case 1)** led to better thermal distribution and lower peak temperatures.
- Copper performs better than aluminium in both configurations due to higher thermal conductivity.


- `README.md` – Project documentation (this file)

---

> 📌 This project demonstrates the critical role of thermal loading type and material selection in heat sink performance optimization.
