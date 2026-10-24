# Jiacheng Xu / Stardust0831

Ph.D. Candidate at Westlake University working on computational chemistry and
materials-science software. My current interests include electronic-structure
post-processing, molecular dynamics, scientific visualization, and reliable
GPU/HPC workflows. I am also a member of the
[CP2K developers team](https://github.com/orgs/cp2k).

## Current Projects

- [SAI HPC Software](https://github.com/AI4SAI/sai-hpc-software) - Uses GitHub
  Actions as the control plane to automate native builds of scientific software
  across HPC cluster partitions, with Slurm scheduling, Apptainer packaging,
  and scientific validation.
- [SSH MountMate](https://github.com/Stardust0831/ssh-mountmate) - A Rust desktop
  app for mounting Linux servers as local drives over SSH/SFTP, with OpenSSH
  config import, rclone integration, and native packages for Windows, macOS,
  and Linux.
- [Multiwfn Cross-Platform Build](https://github.com/Stardust0831/Multiwfn) -
  Reproducible cross-platform builds, CI, release packaging, numerical checks,
  and an experimental MatterViz-based GUI around the official Multiwfn source.
- [multiwfn2vesta](https://github.com/Stardust0831/multiwfn2vesta) - Python
  workflows connecting Multiwfn, VESTA, and electronic-structure outputs for
  real-space analysis and visualization.
- [gau_xtb](https://github.com/Stardust0831/gau_xtb) - A cross-platform,
  standard-library-only Python interface coupling Gaussian to xTB through the
  Gaussian `External` keyword.

## Selected Open-Source Contributions

- [CP2K #6338](https://github.com/cp2k/cp2k/pull/6338) - Integrated a fix for
  lost diagonalization settings and added ELPA redistribution checks with MPI
  regression tests.
- [ABACUS #8192](https://github.com/deepmodeling/abacus-develop/pull/8192) - Added
  shared INPUT value and dependency validation with clear diagnostics and links
  to parameter documentation.
- [ABACUS #7968](https://github.com/deepmodeling/abacus-develop/pull/7968) -
  Stabilized Broyden mixing with a truncated pseudo-inverse for nearly dependent
  history vectors.
- [ABACUS #7665](https://github.com/deepmodeling/abacus-develop/pull/7665) - Added
  GPU regression CI on Slurm and multinode cuSolverMp validation.
- [ABACUS #7688](https://github.com/deepmodeling/abacus-develop/pull/7688) - Fixed
  CUDA-aware MPI synchronization in PGemm.
- CP2K [#5618](https://github.com/cp2k/cp2k/pull/5618) and
  [#5624](https://github.com/cp2k/cp2k/pull/5624) - Removed the UCC requirement
  for cuSOLVERMp 0.7 and later, and added cuSOLVERMp support to the Spack build.
- [MatterViz #377](https://github.com/janosh/matterviz/pull/377) - Fixed periodic
  isosurface coordinates for integer supercells.
- [LAMMPS #5029](https://github.com/lammps/lammps/pull/5029) - Fixed a Kokkos
  `eam/fs/kk` full-neighbor pressure bug.
- ABACUS [#7421](https://github.com/deepmodeling/abacus-develop/pull/7421) and
  [#7424](https://github.com/deepmodeling/abacus-develop/pull/7424) - Fixed
  Molden GTO normalization and Cartesian coordinates, standardized output, and
  added a Multiwfn-specific interface.

## Tools

`Python` `Rust` `Fortran` `C++` `CUDA` `Kokkos` `MPI` `CMake` `GitHub Actions`
`Slurm` `Apptainer` `CP2K` `LAMMPS` `ABACUS` `Multiwfn` `VESTA`
