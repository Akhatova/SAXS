# SAXS
Here you can find a python script for the treatment of a SAXS integrated intensity across the weld.
Please open "SAXS analysis step by step.ipynb".

The script includes:
1. Brief theory
2. SAXS intensity profile analysis
3. EPMA concentration profile analysis
4. Table with experimental and calculated values of M23C6 lattice parameter
5. Calculation of matrix lattice parameter based on:

	a) A.J. Bradley, The lattice spacing of iron-nickel alloys
	
	b) A.Beskrovni, Effect of Cr content on the crystal structure and lattice dynamics of FCC Fe–Cr–Ni–N austenitic alloys
	
6. Electronic contrast
7. Precipitate volume fraction

Unfortunately, the results are still...weird. Unless there is an error in my calculations. You can view my code for those. Hope it's clear enough, I'm not good coder.

I tried an assumtion that the lattice paramater of precipitate is 3 times of the matrix lattice parameter throughout ALL area. In that case, values of the volume fraction of precipitates look more reasonable (3% after PWHT and 5% after 450°C aging), but the peak has shifted from 20 to 10 micrones, which does not correspond to the carbon profile.

