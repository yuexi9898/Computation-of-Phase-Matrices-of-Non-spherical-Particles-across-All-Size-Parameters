# Computation-of-Phase-Matrices-of-Non-spherical-Particles-across-All-Size-Parameters

This database contains data from manuscripts, entitled "Application of Deep Learning to Enhance the Computation of Phase Matrices of Non-spherical Particles across All Size Parameters". The database mainly consists of the scattering matrices data of certain super-spheroids at specific refractive indices. The data is divided into two categories.

1）The first category includes the scattering matrix data for size parameters across all size parameters computed by IITM and IGOM.
The filenames are in the format: ref_{mr}_{mi}_asp_x_n_x_{pij}.dat. In these files, the portion with size parameters less than 50 is computed using IITM, while the portion with size parameters greater than 50 is computed using IGOM. 
For the pij files, the first row represents the scattering angle, ranging from 0° to 180°, with each row corresponding to a specific size parameter. 
The data for the size parameters can be found in the isca.dat file, which also provides information on the extinction coefficient and other properties.

2）The second category includes data for size parameters ranging from 0.1 to 100, computed by IITM. 
The filenames follow the format: Reref_{mr}_{mi}_asp_x_n_x_{pij}.dat. These data have been standardized using P11, representing the ratio of Pij/P11. 
In each file, the first and second columns represent the refractive index, the third and fourth columns correspond to the shape parameters, the fifth column represents the size parameter,
 the sixth column indicates the scattering angle, and the seventh column contains the corresponding scattering matrix data.
