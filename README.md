# MIPRIP

### MIPRIP: The Mixed Integer linear Programming based Regulatory Interaction Predictor

MIPRIP is a software package for R (www.r-project.org) to predict regulators of a gene of interest from gene expression profiles of the samples under study and known regulator binding information (from e.g. ChIP-seq/ChIP-chip databases).
MIPRIP version 1.0

MIPRIP v1.0 was developed to predict the regulators of telomerase genes of Saccharomyces cerevisiae from knockout strains of short telomere length compared to controls (normal telomere length). For this we used (z-transformed) expression data of 269 yeast deletion strains (data is taken from the study by Reimand et al. (Reimand, et al., 2010) ), regulator binding information (for nearly all known yeast transcription factors, mostly taken from YEASTRACT database (www.yeastract.com), and the telomere length class labels were inferred Askree et al. (2004), Gatbonton et al. (2006), Ungar et al. (2009), Shachar et al. (2008) and Ben-Shitrit et al. (2012)(Askree, et al., 2004; Ben-Shitrit, et al., 2012; Gatbonton, et al., 2006; Shachar, et al., 2008; Ungar, et al., 2009) , details can be read in Poos et al.(Poos, et al., 2016) and in the short user manual.

## Downloads

### MIPRIP version 1.0:

    R package MIPRIP v1.0
    MIPRIP v1.0 – Short User Manual

### Data for the case study in the tutorial:

    Edge strength Matrix for S. cerevisiae
    Z-transformed gene expression data (269 samples, data from Reimand et al. (Reimand et al. 2010))
    Activity matrix for the regulators calculated from the gene expression data above
    Phenotypic class labels (telomere length of the 269 deletion strains, taken from Askree et al. (2004), Gatbonton et al. (2006), Ungar et al. (2009), Shachar et al. (2008) and Ben-Shitrit et al. (2012))

Please cite: Poos, A.M., et al. Mixed Integer Linear Programming based machine learning approach identifies regulators of telomerase in yeast. Nucleic Acids Res 2016;44(10):e93.

### MIPRIP version 2.0

MIPRIP 2.0 can be used either to predict regulators of one group of samples (single-mode), to identify significant regulators being different between two groups of samples (e.g. disease vs. control) (dual-mode), or can be applied to more than two groups (multi-mode) to identify the most common and group-specific regulators. It was developed to study the regulation of the telomerase in budding yeast, mouse and human, but MIPRIP can straightforwardly be applied to similar problems integrating gene regulator binding information and expression profiles of samples of e.g. two different phenotypes, disease/healthy controls or treatment/controls. With our newly constructed generic human or mouse regulatory network, MIPRIP 2.0 is applicable to yeast, mouse and human gene expression data. MIPRIP 2.0 can deal with weighted edges between the regulators and the target genes.

Best, you follow the tutorial in the short manual (Downloads) which explains how to use the method along with our case study. 

## Downloads

### MIPRIP 2.0:

    R package MIPRIP 2.0
    MIPRIP 2.0 – Short User Manual

### Regulatory networks:

    Generic human regulatory network
    Generic mouse regulatory network

### Example dataset:

    Gene expression data for the melanoma case study
    Annotation file for the melanoma case study

Please cite: Poos, A.M., et al.Modelling TERT regulation across 19 different cancer types based on the MIPRIP 2.0 gene regulatory network approach.bioRxiv 2019/513259 [url]https://www.biorxiv.org/content/10.1101/513259v1[url].

## References

Askree, S.H., et al. A genome-wide screen for Saccharomyces cerevisiae deletion mutants that affect telomere length. Proc Natl Acad Sci U S A 2004;101(23):8658-8663.

Ben-Shitrit, T., et al. Systematic identification of gene annotation errors in the widely used yeast mutation collections. Nature methods 2012;9(4):373-378.

Gatbonton, T., et al. Telomere length as a quantitative trait: genome-wide survey and genetic mapping of telomere length-control genes in yeast. PLoS Genet 2006;2(3):e35.

Poos, A.M., et al. Mixed Integer Linear Programming based machine learning approach identifies regulators of telomerase in yeast. Nucleic Acids Res 2016;44(10):e93.

Reimand, J., et al. Comprehensive reanalysis of transcription factor knockout expression data in Saccharomyces cerevisiae reveals many new targets. Nucleic Acids Res 2010;38(14):4768-4777.

Shachar, R., et al. A systems-level approach to mapping the telomere length maintenance gene circuitry. Mol Syst Biol 2008;4:172.

Ungar, L., et al. A genome-wide screen for essential yeast genes that affect telomere length maintenance. Nucleic Acids Res 2009;37(12):3840-3849.
