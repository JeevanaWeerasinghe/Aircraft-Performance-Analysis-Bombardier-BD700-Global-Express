# Project Overview
This repository contains a MATLAB-based simulation developed for the "Laboratorio di prestazioni dei velivoli" course at Politecnico di Milano and the associated report. The project evaluates the operational performances of the Bombardier BD700 Global Express (Global 6500) from given polar and thrust data. 
# Key Features
Aerodynamic Modeling: Implementation of a drag polar model accounting for Mach-dependent drag-rise and different flap configurations. \
Level, Climb and Gliding Performance: Anlysis of performance utilizing the International Standard Atmosphere (ISA) model to adjust performance metrics based on altitude. Climb performance analysis includes both standard and energy climbs. \
Flight Envelope Analysis: Computation of level flight boundaries, absolute ceilings, and coordinated turn limits considering both structural load factors and available thrust. \
Take-off & Landing Analysis: Simulation of ground runs to determine Decision Speed and Balanced Field Length for various safety scenarios (AEO and OEI). The employed method is taken from "Airplane design" by Dr. Jan Roskam: while some of parameters used for this method are tabulated coefficients, others are assumptions derived from estimates based on available technical drawings and images. \
Comparison With Competitors: A statistical comparison of wing loading and thrust-to-weight ratios against industry competitors. 
# Repository Structure
LABORATORIO_BD700.m: Main execution script containing the simulation and plot generation. \
Prestazioni_velivolo.pdf: report detailing the mathematical models and performance results. \
Data/: Directory containing aerodynamic polar data and engine thrust tables.
# How to Run
Ensure BD700_polar.txt and BD700_thrust.txt are in the working directory. \
Run LABORATORIO_BD700.m in MATLAB to generate the performance curves and comparative analysis plots.
