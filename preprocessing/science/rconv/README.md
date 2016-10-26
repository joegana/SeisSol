# Rconv

Rconv is a small tool which transforms file given in the Standard Rupture Format (SRF) to the intermediate NetCDF Rupture Format (NRF) which is required by SeisSol for simulating kinematic rupture models.

## Building rconv
You need to have the proj.4 and the NetCDF libraries installed and make sure that the system is able to find them. Then just enter
`scons` in the main folder in order to compile rconv.

## Using rconv
Starting rconv without arguments gives you a short introduction for using the tool. You may furthermore consult the correspdoning [Wiki entry](https://github.com/SeisSol/SeisSol/wiki/Standard-Rupture-Format).