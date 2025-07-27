# A New Dynamical Classification of SPARC Galaxies: Data Products

This repository contains the primary data products associated with the forthcoming paper by Vakhtang Mchedlishvili, which introduces a new morphological classification of 175 galaxies from the SPARC database.

The classification is based on the detailed analysis of the galaxies' dynamical signatures, as revealed by their rotation curves. The goal of this repository is to provide the full set of results for independent review and use by the scientific community.

## Repository Contents

This repository contains two main data products:

### 1. The Complete Graphical Atlas (`/Plots_Atlas`)

The `/Plots_Atlas` folder contains the full graphical atlas of 175 unified rotation curve plots. 

*   **Standardization:** Each plot is presented on a unified coordinate system (`0-85 kpc` vs. `0-450 km/s`) with a fixed aspect ratio to allow for direct visual comparison of different galaxies.
*   **Classification:** Each plot title includes the galaxy's name and its assigned dynamical class.
*   **Benchmark:** A 45° benchmark slope (corresponding to a physical gradient of 10 (km/s)/kpc) is included on each plot for reference.

### 2. The Classification Catalog (`classification_catalog.csv`)

This CSV file contains the final classification for all 175 galaxies. The table includes the following columns:

*   `Galaxy_Name`: The standard SPARC identifier for the galaxy.
*   `Dynamical_Class`: The dynamical class assigned in our work (`Childhood`, `Youth`, or `Old Age`).
*   `Detailed_Morphology`: The standard, detailed morphological type of the galaxy for reference.

## The Classification Scheme (Brief Overview)

The classification is based on a visual and quantitative analysis of the rotation curves, identifying three primary dynamical classes that we propose correspond to different evolutionary stages:

1.  **Class 1: Childhood:** Characterized by high central mass concentration (a steep initial rise, typically above the 45° benchmark) and strong, often complex, oscillatory features across the disk.
2.  **Class 2: Youth:** Characterized by a stabilized core (a less steep rise) but with clear, regular, periodic oscillatory features ("memory waves") in the outer disk.
3.  **Class 3: Old Age:** Characterized by low central mass concentration (a shallow rise, typically below the 45° benchmark) and a very smooth profile with minimal to no oscillatory features.

A full description of the methodology and the physical interpretation of these classes is provided in the main paper (Mchedlishvili, in prep.).

## Usage and Citation

The data and plots in this repository are provided for research and educational purposes. If you use these materials in your scientific publications, please cite the associated paper. The original SPARC data can be accessed at [http://astroweb.cwru.edu/SPARC/](http://astroweb.cwru.edu/SPARC/).
