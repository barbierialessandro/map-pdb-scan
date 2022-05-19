# Map PDB Slice (*Work in progress*)

Adaption of the UCSF Chimera *(1)* animation commands employed in **ResMap** *(2)* for a fast graphical evaluation of **membrane proteins along the z-axis**. 

The script opens up UCSF Chimera and transforms the selected PDB file (aligned along the z-axis, i.e. Orientations of Proteins in Membranes (OPM) database *(3)*) into a calculated density map using only the backbone atoms (*see molmap routine*). The map is scanned along the z-axis and individual trasversal sections at any desidred point can be captured through the Volume Viewer panel (> Features > Planes). This method can be applied to snapshots of Molecular Dynamics Simulation for comparisons with the experimental atomic coordinates. 

The dummy atoms in the OPM files will provide a reference point for checking the transmembrane limits (respectively the blue and red disks), while the initial resolution of the calculated density map can be adjusted according to any need by following the command frameset of UCSF Chimera. 

Example: PDB FILE (6qex)

Version 0.8 May'22 - under development for ChimeraX .  EMAIL > barbierialessandro@hotmail.it with object "Mapdbslice"

*(1) Pettersen EF, Goddard TD, Huang CC, Couch GS, Greenblatt DM, Meng EC, Ferrin TE. J Comput Chem. 2004 Oct;25(13):1605-12
(2) A. Kucukelbir, F.J. Sigworth, and H.D. Tagare, Nature Methods. Volume 11, Issue 1, Pages 63-65, 2014.
(3) https://opm.phar.umich.edu/ *

https://user-images.githubusercontent.com/100777525/168863447-cba56e71-7983-40ca-b9b1-d331c53ced4d.mp4

![OPM_6QEX_2](https://user-images.githubusercontent.com/100777525/168863472-531ac9c8-f2b5-48ac-b53a-57732982bd09.png)
![OPM_6QEX_3](https://user-images.githubusercontent.com/100777525/168863475-9cab2c98-118b-4fb8-b74b-9bb57efb063c.png)
