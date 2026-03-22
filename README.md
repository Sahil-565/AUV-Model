# AUV-Model

This repository contains a MATLAB/Simulink project focused on the modeling and simulation of the Sparus Autonomous Underwater Vehicle (AUV).

## Overview

The aim of this project was to study and simulate the dynamic behavior of the Sparus vehicle using MATLAB scripts and a Simulink model.  
The repository includes source files for parameter definition, vehicle modeling, plotting, and matrix-based calculations, along with graphical outputs generated during the project.

## Tools Used

- MATLAB
- Simulink

## Repository Structure

- `Command.m` – command and execution-related script
- `MeaSim.m` – measurement/simulation-related script
- `Parameters.m` – model parameters
- `Plotting.m` – plotting and result visualization
- `RovModel.m` – vehicle model
- `jacobienne.m` – Jacobian-related computations
- `S_.m` – supporting mathematical function
- `transformation_matrix.m` – transformation matrix calculations
- `yprime.c` – C source file used in the project
- `Added Mass Matrixes for All.mlx` – added mass calculations
- `Drag Forces for All.mlx` – drag force calculations
- `Global Mass Matrixes for Every Conditions.mlx` – global mass matrix analysis
- `Sparus_3D_advance_model.mdl` – main Simulink model
- `Report/Graphs/` – generated graph outputs

## Main Features

- Dynamic modeling of the Sparus AUV
- Simulation in MATLAB/Simulink
- Analysis of added mass and drag effects
- Visualization of simulation outputs through graphs

## Notes

This repository contains the main source files and result plots from the project.  
Generated, cache, and compiled files are excluded through `.gitignore`.

## Author

Sahil Abdullayev
