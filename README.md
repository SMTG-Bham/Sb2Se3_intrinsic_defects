# Sb2Se3_intrinsic_defects

Repository for paper: The Complex Defect Chemistry of Antimony Selenide

DOI: 10.1039/C9TA02022E

Optimised crystal structures of defective Sb2Se3 supercells from density functional theory, calculated using the Vienna *Ab initio* Package (VASP). 
Supplementary data regarding the energies of supercells, and defect formation energies, including contributions from the three corrections mentioned in the article.

Computational Details
-----------------------
The initial 1x3x1 supercells were constructed from a relaxed (atom positions, shape and volume) cell of Sb2Se3, using the HSE06 functional with D3 dispersion corrections (zero-damping, PBE0 parameters from https://www.chemie.uni-bonn.de/pctc/mulliken-center/software/dft-d3/functionals).
Defects were introduced, then further relaxation of the atomic positions was performed using a combination of Quasi-Newton and Conjugate Gradient algorithms.


Requirements
------

A viewer such as [VESTA] (http://jp-minerals.org/vesta/en/) can be used to view the CONTCAR files, and they are in the `POSCAR` input file format useable by VASP.


Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.
