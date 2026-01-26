# Heat Transfer — Heat Sink Material Selection Using FEA

**Course:** Heat Transfer (ME 573)  
**Institution:** Kansas State University  
**Term:** Fall 2023  

---

## Project Overview
This project investigated how heat sink and chip material selection affects the operating temperature of a microelectronic device. A finned heat sink and heat-generating chip assembly was modeled and analyzed using SolidWorks Thermal Simulation, with results validated against hand calculations based on conduction and convection theory.

---

## Technical Scope
- Modeled a finned heat sink–chip assembly with bonded thermal contact
- Applied 25 W heat generation to the chip and convection to all exposed heat-sink surfaces
- Evaluated nine material combinations of heat sink and chip materials
- Applied realistic boundary conditions:
  - Ambient air at 300 K
  - Convection coefficient of 250 W/m²·K
  - Thermal contact resistance of 0.1 K/W
- Performed mesh refinement in regions of high thermal gradients
- Computed temperatures at three key locations (T1, T2, T3)

---

## Analysis & Validation
- Used Fourier’s Law of conduction and extended surface (fin) theory for analytical predictions
- Developed a nodal thermal resistance network to compute expected temperatures
- Compared analytical results against FEM predictions
- Achieved agreement within ~1–2% for most configurations
- Identified alumina heat sink + beryllia chip as the optimal material combination, limiting chip temperature to ~309 K :contentReference[oaicite:1]{index=1}

---

## Skills Demonstrated
- Conduction and convection analysis  
- Extended surface (fin) heat transfer  
- Thermal resistance modeling  
- Finite Element Analysis (FEA) validation  
- Engineering assumptions and uncertainty analysis  

---

