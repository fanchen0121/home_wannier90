# Modified Wannier 90
**!! USE AT YOUR OWN RISK !!**

*The two files are modified from the source code in wannier90. The purpose of it is to generate \*ukk file used for EPW calculations directly from wannier90 run.*
1. added two new variables: 
   exclude  :  number of bands excluded from wannier run in EPW
   alat     :  for lattice constant, which could be obtained from QE scf run
2. when running EPW with the *ukk file generated from this modified wannier90 code, the same *.save folder generated from nscf run should be used. One can just copy the *.save folder from wannier90 run to the folder for epw run, which mean, there is no need to rerun scf or nscf for the epw calculations
3. This version is compatible with wannier90-3.1.0 as in Quantum Espresso 6.6 

**!! USE AT YOUR OWN RISK !!**
