# Data Folder Description

This folder contains data files used in the BIOMI4300 Amplicon Sequencing Project.

## File Descriptions

### ASV Tables

- **ASV_table.tsv**  
  Amplicon Sequence Variant (ASV) count table showing the abundance of each ASV across samples.

- **ASV_table_withSeqNames.tsv**  
  ASV count table including sequence identifiers.

- **ASV_taxonomy.tsv**  
  Taxonomic classification assigned to each ASV.

- **ASVs.fasta**  
  FASTA file containing the nucleotide sequences of each ASV.

---

### Phyloseq Objects

- **raw_physeq.RData**  
  Raw phyloseq object containing ASV counts, taxonomy, and metadata.

- **preprocessed_phyloseq.RData**  
  Processed phyloseq object used for downstream diversity analysis.

---

### Diversity Analysis

- **iNEXT_data.RData**  
  Data prepared for diversity estimation and rarefaction analysis.

---

### Quality Control

- **track_read_counts.RData**  
  Tracks read counts at each step of the DADA2 pipeline.

---

### Raw Sequence Data

- **00_raw_gzipped_fastqs/**  
  Contains raw gzipped FASTQ sequencing files.

- **01_QualityTrimming/**  
  Contains filtered and trimmed FASTQ files after quality control.

---

## Notes

- Files larger than 50 MB are not committed to GitHub according to repository guidelines.
- Raw FASTQ files are stored locally or on the server and may not be included in the repository.
