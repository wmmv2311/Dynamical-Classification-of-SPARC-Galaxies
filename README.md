A Morphological Classification of Galactic Rotation Curves: Data Products
Author: Vakhtang Mchedlishvili
Contact: v.mchedl74@gmail.com
Paper Status: Submitted / Preprint available

Overview
This repository contains the primary data products associated with the research paper "A Morphological Classification of Galactic Rotation Curves: Evidence for a Universal Evolutionary Sequence".

The study analyzes 175 galaxies from the SPARC database, introducing a new dynamical classification scheme based on the detailed morphology of rotation curves. The goal of this repository is to provide the full set of results for independent review and use by the scientific community.

Repository Contents
1. The Classification Catalog (/data)
The file SPARC_Morphological_Catalog.csv contains the final classification and physical parameters for all 175 galaxies.

Column Description:

No: Index number.
Galaxy: The standard SPARC identifier (Galaxy Name).
Alpha (deg): The initial rising slope angle (
�
) measured against a unified scale.
Class: The dynamical class assigned in this work (I, II, or III).
log M_star (M_sun): Stellar Mass in logarithmic solar units.
log SFR (M_sun/yr): Star Formation Rate.
log sSFR (yr^-1): Specific Star Formation Rate.
Source: Original data source reference (e.g., Lelli+16, Leroy+22).
2. The Complete Graphical Atlas (/atlas)
The /atlas folder contains the full graphical atlas of 175 unified rotation curve plots.

Standardization: Each plot is presented on a unified coordinate system to allow for direct visual comparison.
Benchmark: A 45° benchmark slope (corresponding to a physical gradient of 10 km/s/kpc) is included on each plot for reference.
Classification: Each plot title includes the galaxy's name and its assigned dynamical class.
The Classification Scheme
The classification is based on a visual and quantitative analysis of the rotation curves (specifically the initial slope angle 
�
), identifying three primary dynamical classes:

Class I ("Childhood"): 
�
>
75
∘
. Characterized by high central mass concentration (steep rise) and strong, often complex, oscillatory features across the disk. Represents high-tension systems.
Class II ("Youth"): 
45
∘
<
�
≤
75
∘
. Characterized by a stabilized core (moderate rise) and clear, regular, periodic oscillatory features ("memory waves") in the outer disk.
Class III ("Old Age"): 
�
≤
45
∘
. Characterized by low central mass concentration (shallow rise) and a very smooth profile with minimal to no oscillatory features. Represents dynamically relaxed and expanded systems.
A full description of the methodology and the physical interpretation of these classes is provided in the main paper.

Usage and Citation
The data and plots in this repository are provided for research and educational purposes. If you use these materials in your scientific publications, please cite the associated paper:

Mchedlishvili, V. (2025). A Morphological Classification of Galactic Rotation Curves: Evidence for a Universal Evolutionary Sequence.

Acknowledgments
This work utilizes data from the SPARC (Spitzer Photometry and Accurate Rotation Curves) database. We acknowledge Federico Lelli, Stacy McGaugh, and James Schombert for making this resource publicly available. The original SPARC data can be accessed at http://astroweb.cwru.edu/SPARC/.
