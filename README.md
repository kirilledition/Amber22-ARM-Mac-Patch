# Build Amber22 for ARM Macs

[Amber](https://ambermd.org/index.php) is a suite of biomolecular simulation programs.

Repository contains patch file, that changes one of cmake files in AmberTools source code, forcing it to use mambaforge instead of miniconda. This is the only problem in building AmberTools for ARM Macs.

Use patch file on `amber22_src/cmake/UseMiniconda.cmake`
