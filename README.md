# Structural-Analysis-of-Simply-Supported-Beams-with-Point-and-Distributed-Loads
This repository contains a Python script for analyzing a simply supported beam subjected to point loads and uniformly distributed loads (UDL). The script calculates support reactions, shear force, and bending moment diagrams, and visualizes the results using Matplotlib.

## Features

- **Beam Properties**: Input beam dimensions (length, width, height).
- **Support Conditions**: Specify positions of two supports.
- **Load Inputs**: Define multiple point loads and UDLs with their positions.
- **Static Equilibrium**: Calculate support reactions using static equilibrium equations.
- **Shear Force and Bending Moment Diagrams**: Compute and plot shear force and bending moment diagrams.
- **Visualization**: Generate plots for beam diagram, shear force diagram, and bending moment diagram.

- ## Limitations

- **Beam Type**: The script currently supports only simply supported beams. Other beam configurations (e.g., cantilever, fixed beams) are not supported.
- **Load Types**: Limited to point loads and uniformly distributed loads (UDL). Other load types such as moment loads, triangular loads, or varying loads are not supported.
- **Input Validation**: Basic input validation is implemented, but more robust error handling and validation could be added to handle edge cases and incorrect inputs more gracefully.
- **User Interface**: The script uses command-line inputs, which may not be user-friendly for all users. A graphical user interface (GUI) could enhance usability and accessibility.
- **Units**: The script assumes all inputs are in meters (m) and kilonewtons (kN). Other units are not supported, which may limit its use in different contexts or regions with different standard units.
- **Complex Load Combinations**: The script does not handle complex combinations of loads or dynamic loading conditions. It is designed for static load analysis only.
- **Material Properties**: The script does not account for different material properties of the beam, assuming a homogeneous material with a constant moment of inertia.

### Prerequisites
- Python 3.x
- Required Python packages: `numpy`, `matplotlib`



   
