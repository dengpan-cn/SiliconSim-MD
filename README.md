# SiliconSim-MD
Scripts to prepare equilibrium silicon melts and simulate microscopic processes under radiation.

1. getEquSiO2Melt.lmp: LAMMPS scripts to prepare equilibrium silicon melts.
2. doRadiaSim.lmp: LAMMPS scripts to simulate microscopic processes under radiation.
3. initCrtstalSiO2.data: configurations of silicon crystal which is generated using ATOMSK (https://atomsk.univ-lille.fr).
4. SiO2T0.1.data: configuration of amporphous silicon at T = 0.1K.
5. tablePotMorse.dat: interaction potential (without coulombic potential), Morse potential in table style, used to simulate silicon.
6. tablePotZblandMorse.dat: mixed interaction potential (without coulombic potential), used to simulate dynamic processes under radiation.

Reference

[1] A. Pedone, G. Malavasi, M. C. Menziani, A. N. Cormack, and U. Segre, The Journal of Physical Chemistry B 110, 11780 (2006).
[2] J. F. Ziegler, J. P. Biersack, and U. Littmark. In The Stopping and Range of Ions in Matter, volume 1, New York, 1985. Pergamon.   
