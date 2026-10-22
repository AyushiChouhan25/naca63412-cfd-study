# naca63412-cfd-study
CFD study of a NACA 63412 wing in SimScale (k-omega SST, Re ≈ 2×10^5): mesh sensitivity and angle-of-attack analysis with Python post-processing.
# NACA 63412 CFD Study: Mesh Sensitivity and Angle of Attack

CFD study of a non-tapered NACA 63412 wing (chord 0.2 m, span 1.2 m, 15 m/s, Re ≈ 2×10^5) using SimScale (k-omega SST, steady-state) with Python post-processing.

## Contents
- `post_processing.ipynb`: force averaging, coefficient and L/D calculation, plots
- `data/`: exported SimScale force histories

## SimScale projects
- Coarse mesh: <link>
- Medium mesh: <link>
- Fine mesh: <link>

## Known issues
See Section 3.6 of the report: the 12° case was run at 16°, and the 8° case is anomalous and not physically reliable.

## Report
<link to PDF>
