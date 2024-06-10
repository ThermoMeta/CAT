Computational Science helps generate streamlines and isotherms. We further match specific physical quantities to establish a conformal mesh. Take Fig. 2a-d as an example to present the process.

1. System requirements
COMSOL Multiphysics 6.0 & Windows 11

2. Installation guide
COMSOL Multiphysics is a commercial software with detailed installation instructions on the official website. Install the trial version for simplicity. It takes about 15 minutes for installation.

3. Demo
Our design process mainly has two parts: Mesh Generation (see the .mph file with the same name) and Thermal Cloak (see the .mph file with the same name).
Generating streamlines and isotherms: Mainly outputting two files, i.e., "Streamlines.txt" and "ks.txt." "Streamlines.txt" maps a point in the bulk to the boundary via a streamline. "ks.txt" is used to match the boundary normal heat flux.
Designing a thermal cloak: "Streamlines.txt" and "ks.txt" are input as two interpolation functions.
Running these two files takes about a dozen seconds.

4. Instructions for use
Click the "Compute" button to obtain all results.