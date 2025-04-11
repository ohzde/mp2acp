# Supporting Data for ACP Development in Accurate MP2/CBS Energy Prediction

This repository contains the supporting data for the development of Atom-Centered Potentials (ACPs) aimed at improving the accuracy of HF/aDZ to that of MP2/CBS in electronic energy predictions.

If you use these data, please cite the following sources:

- [Link1](link1)
- [Link2](link2)

--

The `Data/` contains spreadsheets with reference, base, and ACP-corrected energies for different ACPs. Data are provided for:

- The training set
- The TABS test set
- The MolDef test set

--

The `Geometries/` folder includes molecular geometries in `.xyz` format for the training and both of the test sets.

--

The `Reference_calculations/` directory contains:

- ORCA output files for reference energy calculations of all datasets
- Gaussian output files for ACP evaluation on TABS and MolDef test sets

Note: for BH9, the reference calculations are provided as separate output files for MP2/aDZ, MP2/aTZ, and MP2/aQZ. The first two letters of the file name indicate the basis set used (e.g., DZ_ corresponds to MP2/aDZ). For the rest of the training set (BSE49, S66X10, and X2_HX, which includes single atoms and diatomics), all MP2/aDZ, MP2/aTZ, and MP2/aQZ calculations are included in a single output file per system.

---

