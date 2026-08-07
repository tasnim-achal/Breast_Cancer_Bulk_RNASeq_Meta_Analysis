# Breast_Cancer_Bulk_RNASeq_Meta_Analysis 
# Bulk RNA-Seq Analysis of GSE87340

[![R-version](https://img.shields.io/badge/R-%E2%89%A5%204.0.0-blue.svg)](https://www.r-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GEO Accession](https://img.shields.io/badge/GEO-GSE87340-brightgreen.svg)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87340)

## 📌 Project Overview
This repository contains a complete, end-to-end bioinformatics pipeline for analyzing high-throughput bulk RNA-sequencing data from the NCBI GEO dataset **GSE87340**. 

The pipeline focuses on differential gene expression profiling, functional pathway enrichment, and weighted gene co-expression network analysis (WGCNA) to identify key biomarkers, hub genes, and biological mechanisms.

---

## 📊 Dataset Profile: GSE87340

* **Organism:** *Homo sapiens*
* **Platform:** Illumina HiSeq 2500 (Bulk RNA-Sequencing)
* **Design:** Paired tumor vs. matched adjacent normal tissue samples
* **Primary Objective:** Identify conserved differentially expressed genes (DEGs) and co-expression network modules.

---

## 📁 Repository Structure

```text
Bulk_RNASeq_Meta-anlysis-/
├── Data/                   # Input count matrices, phenoData, and processed .RData objects
├── Scripts/                # Sequential R scripts for QC, DEG analysis, and WGCNA
├── figures/                # Visualizations (Volcano plots, Heatmaps, WGCNA Module-Trait relationships)
├── tables/                 # Summary tables (DEGs, GO/KEGG pathways, Hub genes)
└── README.md               # Project documentation
## 📚 References & Citations

### Primary Dataset
* **GSE87340:** Gene Expression Omnibus (GEO), NCBI.  
  * Accession: [GSE87340](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87340)
  * Edgar, R., Domrachev, M., & Lash, A. E. (2002). Gene Expression Omnibus: NCBI gene expression and hybridization array data repository. *Nucleic Acids Research*, 30(1), 207-210.

### R Packages & Analytical Tools
1. **DESeq2 (Differential Expression):**  
   Love, M. I., Huber, W., & Anders, S. (2014). Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. *Genome Biology*, 15(12), 550.
2. **WGCNA (Weighted Co-expression Networks):**  
   Langfelder, P., & Horvath, S. (2008). WGCNA: an R package for weighted correlation network analysis. *BMC Bioinformatics*, 9(1), 559.
3. **clusterProfiler (Functional Enrichment):**  
   Wu, T., Hu, E., Xu, S., Chen, M., Guo, P., Dai, Z., ... & Yu, G. (2021). clusterProfiler 4.0: A universal enrichment tool for interpreting omics data. *The Innovation*, 2(3), 100141.
4. **limma (Linear Models for Microarray & RNA-Seq):**  
   Ritchie, M. E., Phipson, B., Wu, D., Hu, Y., Law, C. W., Shi, W., & Smyth, G. K. (2015). limma powers differential expression analyses for RNA-sequencing and microarray studies. *Nucleic Acids Research*, 43(7), e47-e47.
5. **GEOquery (Data Retrieval):**  
   Davis, S., & Meltzer, P. S. (2007). GEOquery: a bridge between the Gene Expression Omnibus (GEO) and BioConductor. *Bioinformatics*, 23(14), 1846-1847.
