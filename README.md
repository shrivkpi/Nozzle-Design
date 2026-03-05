# Supersonic Nozzle Design using Method of Characteristics

This project focuses on the design of a **minimum-length supersonic nozzle** using the **Method of Characteristics (MoC)**. The method is used to solve the governing equations of compressible flow and generate a nozzle contour that enables smooth, shock-free expansion of the flow to a desired exit Mach number. :contentReference[oaicite:0]{index=0}

## Project Overview

The Method of Characteristics converts the nonlinear partial differential equations governing supersonic compressible flow into characteristic relations that can be solved along specific directions in the flow field. By constructing a characteristic mesh, the flow properties such as Mach number, flow angle, and pressure are computed iteratively, allowing the contour of the nozzle wall to be determined. :contentReference[oaicite:1]{index=1}

In this project:

- A **minimum-length nozzle** configuration is designed starting from the throat where the flow reaches Mach 1.
- Characteristic lines are generated to compute the expansion of the flow in the divergent section.
- The wall contour is obtained from the intersection of characteristic lines with the nozzle boundary.
- The final nozzle shape is calculated to achieve a target **exit Mach number of approximately 2.5**. :contentReference[oaicite:2]{index=2}

## Simulation

To verify the design, a **2D inviscid flow simulation** of the nozzle was performed in ANSYS Fluent using a CAD model created in SolidWorks. The simulation produced an exit Mach number of approximately **2.47**, closely matching the design target. :contentReference[oaicite:3]{index=3}
