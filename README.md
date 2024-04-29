# BK_NS11021_SI
This is the SI data repository for paper on BK channel activator NS11021: Nordquist, Jia, Chen. "Small molecule NS11021 promotes Big K^+ channel activation by increasing inner pore hydration." 2024, in prep.

It contains the gromacs-style (itp) topology and parameter files for the system, including the small molecule NS11021 as well as the plumed run files for the umbrella sampling simulations used.

## Contents:
| Name          | Description |
|---------------|-------------|
| toppar/       | Gromacs-style (*.itp) topology and parameter files for the charmm36m force field, including the ligand NS11021 | 
| restraints/   | Gromacs-style harmonic restraint files |
| 24.pdb        | System snapshot with NS11021 CoM 24 Ang from filter |
| NS11021_plumed24.dat  | Plumed file for Umbrella sampling of NS11021 position, specifically the window centered at CoM distance 24 Ang from filter | 
| system.pdb    | Overall system coordinates used for the BK channel restraints (restraints/PROAB.itp) |
| prod100ns.mdp | Gromacs-style MD parameters file |
| K_plumed22.dat | Plumed file for Umbrella sampling of K^+ position, specifically the window centered at CoM distance 22 Ang from filter | 
