# code_generation

MATLAB and Simulink examples for Kalman filtering and Goldschmidt division, covering floating-point prototypes, fixed-point models, and code-generation workflows.

## Project Layout

- [`KF_Project/KF_Demo/`](KF_Project/KF_Demo/): baseline MATLAB functions and Live Script examples.
- [`KF_Project/KF_Demo_Fixed/`](KF_Project/KF_Demo_Fixed/): fixed-point Kalman-filter and divider examples.
- [`KF_Project/KF_Demo_Model_Gen/`](KF_Project/KF_Demo_Model_Gen/): Simulink models for C and HDL workflows, including testbench and cosimulation models.

## Getting Started

Read the existing [project notes](KF_Project/README.txt), then begin with [`KF_Demo_S1.mlx`](KF_Project/KF_Demo/KF_Demo_S1.mlx) for the baseline Kalman-filter example.

Use MATLAB for scripts and Simulink for `.slx` models. Fixed-point and code-generation steps need the corresponding MathWorks products and configured external tools. Adapt the compiler and simulator paths in the project notes to your machine.
