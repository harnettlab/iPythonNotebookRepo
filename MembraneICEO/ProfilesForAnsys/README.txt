Profiles for ANSYS

Wall velocities were calculated from exported Maxwell electric field data using this code: 
https://github.com/harnettlab/iPythonNotebookRepo/blob/master/MembraneICEO/PoreZetaVCalc3.ipynb

The filenames give information on what was in each model

for instance v1_p40_m10_e20_s2000_geom.txt

is the geometry file for reading the shape into ANSYS
v1: voltage was 1V from electrode to electrode
p40: the pore diameter was 40 nm
m10: the membrane thickness was 10 microns
e20: the electrode-to-electrode separation was 20 microns
s2000: the spacing between adjacent pores (or diameter of the domain) was 2000 nm.

There's a related file called v1_p40_m10_e20_s2000_prof.txt that gives the velocity vectors for the same simulation.


In these simulations, the membrane is always centered between the two electrodes, so in the above example there were 5 microns of water on each side of the membrane.
