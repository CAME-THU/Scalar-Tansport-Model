# Scalar-Tansport-Model
Scalar transport sover can be enbeded in SOWFA solver to evaluate wake recovry in wind turbine flows.

## Compile the scalarTransport solver
The solver is located at 'pisoFoamTurbine.ALMAdvanced.scalarTransort'.
As for SOWFA simulation, put 'pisoFoamTurbine.ALMAdvanced.scalarTransort' into 'applications\solvers\incompressible\windEnergy\'. And then use 'wmake' to compile solver.

## Setup of case
As for folder 'Example_Case', put file 'sPhi' in your '0' folder, and copy parameters of file 'transportProperties' and then add them into your 'transportProperties' file, and set 'fvSchemes' as well as 'fvSolution' of your case byu reference of two files in folder 'system'.
