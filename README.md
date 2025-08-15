# Heat_absorption_by_solar_panels
##  Overview
This project demonstrates the heat flux and temperature distribution on a **silicon-based solar panel** due to radiation from a nearby heat source.  
A **steel ball** is modeled as the heat-generating object, placed above the panel.  
The simulation focuses solely on **radiative heat transfer**, neglecting free convection effects.

##  Objective
- To analyze the **heat flux** reaching a solar panel from an adjacent heat source.
- To visualize the **temperature distribution** across the panel surface.
- To study the effect of **surface-to-surface radiation** between two bodies.

## Modeling Steps
1. **Setup**
   - Open **ANSYS Workbench**.
   - Create a **Steady-State Thermal Analysis** system.
2. **Material Properties**
   - Solar panel: Silicon.
   - Heat source (ball): Steel.
3. **Geometry Import**
   - Model consists of a flat panel and a spherical object above it.
4. **Boundary Conditions**
   - Internal heat generation in ball: **10,000 W/m³**.
   - Surface-to-surface radiation between ball and panel:
     - Emissivity: **0.7** (typical for uncovered solar panels).
     - Ambient temperature: **22 °C**.
5. **Solver Settings**
   - Use **substeps** for convergence.
6. **Meshing**
   - Apply linear mesh.
7. **Solution**
   - Solve for steady-state conditions.

##  Results
- **Heat Flux Plot** – Isometric & side views showing radiation intensity on the panel.
- **Temperature Distribution Plot** – Gradient from ambient temperature due to incoming radiation.

## 📂 Repository Structure
