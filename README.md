# CST-Microstrip-Line-50Ohm
This project is a modeling and simulation of a 50 Ohm Microstrip Transmission Line using CST Studio Suite. It serves as an introduction to basic RF circuit analysis.
# CST 50 Ohm Microstrip Line Modeling

## Project Goal
The main goal of this project is to create the 3D geometry of a **50 Ohm Microstrip Transmission Line** in CST Studio Suite. This structure is very important for many Radio Frequency (RF) applications.

## Key Parameters Used
* **Design Impedance (Z0):** 50 Ohms (Standard value for RF systems).
* **Software Used:** CST Studio Suite (for Electromagnetic simulation).
* **Substrate Material:** Non-magnetic Oxide (MgO).
* **Relative Permittivity (Epsilon r):** 9.7 (Material property).
* **Substrate Height (h):** 0.5 mm.
* **Calculated Line Width (w):** Approximately 0.48 mm (This width ensures the 50 Ohm impedance).

## Next Steps (Simulation)
After the geometry is ready, the next steps are to run the simulation and check the S-Parameters. We will look closely at:
* $S_{11}$ (Return Loss): To see how well the line matches the 50 Ohm port.
* $S_{21}$ (Insertion Loss): To measure the signal loss through the line.
