# Fluid-Structure Interaction: Turek-Hron FSI benchmarks simulation using OpenFOAM, CalculiX and preCICE

This is a part of our undergraduate project titled 'Aeroelastic modelling of insect flight' carried out in the school of Mechanical sciences, Indian Institute of Technology Goa.

* Authors: Nithin Adidela, Revanth Sharma, Y. Sudhakar

* email: {nithin.adiela.16003,revanth.sharma.16003,sudhakar}@iitgoa.ac.in

This case was inspired by the contribution from Derek Risseeuw (TU Delft). 

Fluid part of the simulation is performed on OpenFOAM v7. Solid part of the simulation is performed on CalculiX 2.15. Coupling of the simulation is achieved by preCICE-1.6.1

The  simulation is tested in serial mode in a machine running Ubuntu 18.04. The mesh used is coarse and the user is free to make the mesh finer to achieve a better agreement with the standard case after properly understanding the blockMeshdict file.

## Parts

There are 3 FSI benchmarks each defined by different fluid as well as solid material parameters, and different inlet boundary conditions. All 3 can be found inside this repository
