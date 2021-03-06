Molecular Dynamics With Constraints(mdwc)
==========================================

The molecular dynamics with constraints (mdwc) package is a command line open source python program. It does constraint molecular dynamics with either NPT (keeping pressure constant with the Parrinello Rahman lagrangian, and keeping the temperature constant with the Nose thermostat) or NVT (keeping the temperature constant with the Nose thermostat). mdwc does constraint dynamics following the SHAKE algorithm, mdwc constraints bond distances, angles, atomic positions, lattice parameters (a, b, c), angles between lattice vectors, and volume of the unit cell.

Mdwc has the mdwc_ script to interface the mdwc code with an external first principles code for the calculations of energies and forces, so far, the only supported DFT code is [Abinit](https://www.abinit.org/). You can use the mdwc functions to carry on constrained molecular dynamics with other first principals codes (for more details look at the jupyter notebook section)


mdwc requirements
-----------------
For its correct functioning mlmd needs the following codes:

1. [Python](https://www.python.org/download/releases/2.7/ "Python") = 2.7

2. [Numpy](http://www.numpy.org/ "Numpy") >= 1.1 1

* [Abinit](https://www.abinit.org/) to use the mdwc_

mdwc user manual
----------------


Contributors
------------
* Prof. Aldo H. Romero [West Virginia University] 

* Arturo Hernandez [West Virginia University] (Developer)

* Uthpala Herath   [West Virginia University] (Simulation and testing) 

* Pedram Tavazohi  [West Virginia University] (Simulation and testing)
