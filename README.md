# kpoints
k-point paths for different lattice types
The data in this repository is copied from the website "AFlow - Automatic - FLOW for Materials Discovery", http://aflowlib.org/ .

It contains several k-point paths in Brillouin zone of different lattice types.
Those paths are drawn, e.g. on https://en.wikipedia.org/wiki/Brillouin_zone [accessed 2015-06-19].

The format of the files is that of the KPOINTS file in VASP (the Vienna Ab initio simulation package, see https://www.vasp.at/ , http://cms.mpi.univie.ac.at/vasp/vasp/Strings_k_points_bandstructure_calculations.html ).
The first 4 lines are header (the very first says which lattice type we have), followed by pairs of line segments like

   0.000   0.000   0.000   ! \Gamma  
   0.500   0.500   0.500   ! L  

Those are the coefficients h, k and l, an explanation mark and the name of the point.
The corresponding k-vector is: h b1 + k b2 + l b3, where b1, b2 and b3 are reciprocal lattice vectors (mind a factor of 2pi, depending on convention).

If you use these files, you may be required to cite the following papers. See the AFlow website for details.

[1] R. H. Taylor, F. Rose, C. Toher, O. Levy, M. Buongiorno Nardelli, and S. Curtarolo, A RESTful API for exchanging Materials Data in the AFLOWLIB.org consortium, Comp. Mat. Sci. VVV, PPP (2014).
doi: http://dx.doi.org/10.1016/j.commatsci.2014.05.014
pdf: http://materials.duke.edu/auro/AUROARTICULA/1403.2642v3.pdf

[2] W. Setyawan and S. Curtarolo, High-throughput electronic structure calculations: challenges and tools, Comp. Mat. Sci. 49, 299-312 (2010).
doi: http://dx.doi.org/10.1016/j.commatsci.2010.05.010
pdf: http://materials.duke.edu/auro/AUROARTICULA/j.commatsci.2010.05.010.pdf

[3] W. Setyawan, R. M. Gaume, S. Lam, R. S. Feigelson, and S. Curtarolo, High-Throughput Combinatorial Database of Electronic Band Structures for Inorganic Scintillator Materials, ACS Comb. Sci. 13(4), 382-390 (2011).
doi: http://dx.doi.org/10.1021/co200012w
pdf: http://materials.duke.edu/auro/AUROARTICULA/acs_comb_sci_co200012w.pdf
suppl: http://materials.duke.edu/auro/AUROARTICULA/acs_comb_sci_co200012w_suppl.pdf

[4] S.Wang, Z. Wang, W. Setyawan, N. Mingo, S. Curtarolo, Assessing the thermoelectric properties of sintered compounds with high-throughput ab-initio calculations, Phys. Rev. X 1, 021012 (2011).
doi: http://dx.doi.org/10.1103/PhysRevX.1.021012
pdf: http://materials.duke.edu/auro/AUROARTICULA/PhysRevX.1.021012.pdf
suppl: http://materials.duke.edu/auro/AUROARTICULA/PhysRevX.1.021012_suppl.pdf

