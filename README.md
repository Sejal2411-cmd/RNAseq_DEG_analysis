# RNA-seq Differential Gene Expression Analysis

This project performs RNA-seq differential gene expression analysis using DESeq2 in R to identify genes that are significantly expressed between Knockdown (KD) and Control samples.

## Dataset
RNA-seq count dataset containing gene expression values for control and knockdown samples.

## Workflow
1. Import RNA-seq count dataset
2. Create DESeq2 dataset
3. Perform differential expression analysis
4. Filter significant genes using adjusted p-value
5. Generate visualizations (volcano plot, expression distribution)
6. Perform Gene Ontology enrichment analysis

## Tools & Packages
- R
- DESeq2
- ggplot2
- clusterProfiler
- org.Hs.eg.db

## Output
- Differential gene expression results
- Volcano plot visualization
- GO enrichment analysis

## Author
Sejal Sharma  
MSc Multidisciplinary Biomedical Science (Informatics)  
University of Alabama at Birmingham

## Project Structure
RNAseq_DEG_analysis
│
├── Data Analysis.Rmd        # RNA-seq differential expression analysis
├── RNAseq.tsv               # Input RNA-seq dataset
└── README.md                # Project documentation
