# SGCRNAs
SGCRNAs is a library for SGCRNA (Spectral-clustering Generalised Correlation Regression Network Analysis).  
SGCRNA is a method for the analysis of co-expression networks, grounded in correlation and linear relationships. This method is applicable not only to transcriptomic data, but also to metagenomic, proteomic, and metabolomic variables, and accommodates a wide range of dataset types, including standard samples, time-course data, single-cell data, and spatially resolved datasets.

## Installation
Download Julia 1.11 or later, preferably the current stable release. You can add SGCRNAs using Julia's package manager, by typing `] add SGCRNAs` or `using Pkg; Pkg.add("SGCRNAs")` in the Julia prompt.  
We recommend installing the following optional packages:
- RCall: This is useful for executing R scripts within Julia, which is often necessary when performing Gene Ontology analysis on transcriptomic data.
- JLD2: Allows for the temporary saving of computational results.

## Related Publication
If you use this package in your research, please cite the following paper: T. Osone, et al., SGCRNA: Spectral Clustering-Guided Co-Expression Network Analysis Without Scale-Free Constraints for Multi-Omic Data, bioRxiv, 2025. https://www.biorxiv.org/cgi/content/short/2025.04.27.650628v1