# BioE230-project
Project files for BioE 230 final project.  Project partners: Ben and Arianna


Summary
We have used the LAMMPS version 2019 software package provided by CCBM Biotheory computing cluster at University of California, Merced. This project simulates the brownian dynamics of a bead-string polymer. The design of the polymer includes a chain of beads connected with FENE bonds and with each bead experiencing a random force due to Brownian motion. We use the Langevin thermostat and periodic boundary conditions to run the simulation in 2 dimensions. This simulated Brownian motion for diffusion of a polymer
Using a Jupyter notebook we created a polymer and simulated active Brownian motion to observe the difference between active and non-active Brownian motion

Installation
LAMMPS 2019 was used to run the lammps simulation
LAMMPS simulation file is poly.lam and the input file is poly1.input
To execute poly.lam use the command:
lmp -in poly.lam

In order to change the temperature or number of obstacles edit the appropriate fields in the poly.lam executable


Output will be images which were turned into GIFs using imageJ of the trajectories of the polymer with and without obstacles, and at different temperatures
Output files will also include trajectory and topology output files
Initial concept was to use these files to track the trajectory of the polymer, but many of the trajectory analysis packages for LAMMPS are not available for Windows machine, therefore this was abandoned



In order to execute the Jupyter notebook download and run in your Jupyter notebook or other python code reader (i.e. Spyder)

Output will be two animations that are plotted inline with the code


Results
Resutls of the LAMMPS simulations can be seen with the link to the Google slides presentation looking at the polymer at different temperatures and with different number of obstacles
As a function of temperature the polymer moves faster as the thermal energy of the system increases
As a function of obstacles the polymer seems to get "stuck" more as the number of obstacles increases

With the Python scripted polymer simulating active Brownian motion we were able to get the polymer to be created without overlapping beads and we were able to get the polymer to move in a serpentine fashion


