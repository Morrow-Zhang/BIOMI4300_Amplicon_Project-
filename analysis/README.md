# Analysis Folder Description

This folder contains all analysis scripts and output reports used in the BIOMI4300 Amplicon Sequencing Project.  
Each step corresponds to a stage in the DADA2 workflow and downstream diversity analysis.



## Workflow Steps

### 00_FastQC/

Contains FastQC quality control reports used to evaluate raw sequencing read quality before trimming.


### 01_QualityTrimming

- **01_QualityTrimming.Rmd**  
  Performs quality filtering and trimming of raw FASTQ files using DADA2.

- **01_QualityTrimming.html**  
  Rendered report showing quality profiles, trimming decisions, and filtering results.



### 02_AssignASVs

- **02_AssignASVs.Rmd**  
  Performs ASV inference using DADA2, including:
  - Error rate learning  
  - Dereplication  
  - ASV inference  
  - Chimera removal  
  - Taxonomic assignment  

- **02_AssignASVs.html**  
  Rendered output report showing ASV generation and taxonomy assignment results.


### 03_PreProcessing

- **03_PreProcessing.Rmd**  
  Constructs phyloseq objects and prepares data for diversity analysis.

- **03_PreProcessing.html**  
  Output report documenting preprocessing steps and phyloseq creation.


### 04_Biodiversity

- **04_Biodiversity.RMD**  
  Performs alpha and beta diversity analysis, including:
  - Rarefaction analysis  
  - Diversity calculations  
  - Community comparison  

- **04_Biodiversity.html**  
  Output report presenting diversity results and visualizations.


## Notes

- `.Rmd` files contain analysis code and documentation.
- `.html` files are rendered outputs submitted as reports.
