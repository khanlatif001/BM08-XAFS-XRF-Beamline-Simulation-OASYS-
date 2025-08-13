# BM08-XAFS-XRF-Beamline-Simulation-OASYS-
OASYS simulation setup for BM08-XAFS/XRF beamline at SESAME synchrotron, including optical layout, ray-tracing, and energy resolution studies.

This repository contains the OASYS simulation workflow for the BM08-XAFS/XRF beamline at SESAME. The simulation was developed to model and optimize the beamline optics and performance.

📂 Contents
BM08-XAFS_XRF.ows – OASYS workflow file containing the beamline simulation setup.

🛠 Requirements
To run the simulation, you need:

OASYS1 – Open Source Synchrotron Simulation Environment
Installation guide: https://github.com/oasys-kit/OASYS1

Required OASYS add-on packages:

Synchrotron Radiation Workshop (SRW)

ShadowOui (for ray tracing)

XOPPY (for X-ray optics components)

You can install these from the OASYS Add-on Manager.

▶ How to Open the Simulation
Install OASYS and required add-ons.

Download this repository or clone it:




git clone https://github.com/USERNAME/BM08-XAFS_XRF-Simulation.git
Open OASYS.

Go to File → Open, then select the .ows file from this repository.


Run the simulation by clicking Run in OASYS.


📄 Notes
This simulation represents the BM08-XAFS/XRF beamline layout with realistic parameters.

It can be modified to test different optical configurations, source parameters, or energy ranges.

Designed for academic and research purposes.


📜 Citation

If you use this simulation in your research, please cite:


Latif U. Khan, Sergio Lordano and Bernd Meyer BM08-XAFS/XRF Beamline, SESAME Synchrotron Light Source, OASYS Simulation Workflow
