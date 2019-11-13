# MIPRIP

### MIPRIP: The Mixed Integer linear Programming based Regulatory Interaction Predictor

MIPRIP is a software package for R (www.r-project.org) to predict regulators of a gene of interest from gene expression profiles of the samples under study and known regulator binding information (from e.g. ChIP-seq/ChIP-chip databases).
It was initially developed to study the regulation of the telomerase genes of Saccharomyces cerevisiae from knockout strains of short telomere length compared to controls (normal telomere length) (MIPRIP v1).
The extended version of MIPRIP (MIPRIP 2.0 or v2) can be used either to predict regulators of one group of samples (single-mode), to identify significant regulators being different between two groups of samples (e.g. disease vs. control) (dual-mode), or can be applied to more than two groups (multi-mode) to identify the most common and group-specific regulators. It was developed to study the regulation of the telomerase in human, but MIPRIP can straightforwardly be applied to similar problems integrating gene regulator binding information and expression profiles of samples of e.g. different phenotypes, disease/healthy  or treatment/controls. With our newly constructed generic human or mouse regulatory network, MIPRIP 2.0 is applicable to human, mouse and yeast gene expression data.

Best, you follow the tutorial in the short manuals which explains how to use the method along with our case studies.

For more details you can read our papers:

Poos, A.M., et al. Modelling TERT regulation across 19 different cancer types based on the MIPRIP 2.0 gene regulatory network approach. bioRxiv 2019, 513259; doi: https://doi.org/10.1101/513259.

Poos, A.M., et al. Mixed Integer Linear Programming based machine learning approach identifies regulators of telomerase in yeast. Nucleic Acids Res 2016;44(10):e93.

