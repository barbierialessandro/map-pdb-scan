# Map PDB Slice 
Version 0.8 May'22 - under development - barbierialessandro@hotmail.it with object "Mapdbslice"

Adaption of the UCSF Chimera *(1)* animation commands employed in **ResMap** *(2)* for a fast graphical evaluation of **membrane proteins along the z-axis**. 

The script opens UCSF Chimera up and transforms the selected PDB file aligned along the z-axis (i.e. (OPM) database *(3)*) into a calculated density map using only the backbone atoms (*see molmap routine*). The map is scanned along the z-axis and individual trasversal sections at any desired point can be captured through the Volume Viewer panel (> Features > Planes). This method can be applied to snapshots of Molecular Dynamics Simulation for comparisons with the experimental atomic coordinates. 

The dummy atoms in the OPM files will provide a reference point for checking the transmembrane limits (respectively the blue and red disks), while the initial resolution of the calculated density map can be adjusted according to any need by following the command frameset of UCSF Chimera. The increase or decrease of the size of the trasversal sections will also give indications of the inclination of secondary structure elements along the z-axis. 

![OPM_6QEX_5_95_and_6_108_front](https://user-images.githubusercontent.com/100777525/170260798-9c13f13f-7684-4e3a-9939-edce5535d076.png)

https://user-images.githubusercontent.com/100777525/168863447-cba56e71-7983-40ca-b9b1-d331c53ced4d.mp4

Example: PDB FILE (6qex)

*(1) Pettersen EF, Goddard TD, Huang CC, Couch GS, Greenblatt DM, Meng EC, Ferrin TE. J Comput Chem. 2004 Oct;25(13):1605-12
(2) A. Kucukelbir, F.J. Sigworth, and H.D. Tagare, Nature Methods. Volume 11, Issue 1, Pages 63-65, 2014.
(3) Orientations of Proteins in Membranes (OPM) database https://opm.phar.umich.edu/ *
