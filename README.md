# Research_Data_Foundations_Final_Project
This is the final project for my participation in CU Boulder's Research Data Foundations Camp in August of 2025.

Information from the Data Camp can be found at: https://cu-boulder-crdds.github.io/Research-Data-Foundations-Camp-2025-August/

Data Files:

M5_out_278.00.dat contains the data from the M5 simulation in Mastrobuono-Battisti et. al (2023), procured by request from the authors.
The columns are: x y z vx vy vz mass. Each line represents a "star" (or black hole) in the system.
the units of positions are in parsecs, velocites are in km/s, and masses are in solar masses.

M5_t278.00_CoM.tsv contains the data from M5_out_278.00.dat transformed into the reference frame of the center of mass of the binary black hole system with an additional colun to indicate which nuclear star cluster (NSC) the star originated in (1 or 2).

M5_t278.00_CoM_mks.tsv contains the same data as M5_t278.00_CoM.tsv, but with units converted to mks units.

These data tranformations, production of these two files, and further data analysis and visualization is done in NSC_statistical_analysis.ipynb.