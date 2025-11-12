# Transient-Heat-Transfer-Simulation-of-Wire-Arc-Additive-Manufacturing-Using-Abaqus-User-Subroutines
A user subroutine implementation composed of DFLUX and UEPACTIVATIONVOL is provided in this module which simulates the heat input, element activation, and nodal temperature extraction for WAAM process of a multi-layer wall. 
DFLUX: A DEFLUX user subroutine is used to simulate the Goldak heat source which is frequently used in wire arc additive manufacturing and other laser based AM processes such as LPBF or DED.
UEPACTIVATIONVOL: This user subroutine is used to activate elements based on the event series (or G-Codes).
OIRENT: This user subroutine is used to calculate the centroidal location of elements. These spatial data is used to assign activation time to elements. 
