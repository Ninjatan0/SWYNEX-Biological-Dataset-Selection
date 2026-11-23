# SWYNEX – Biological Dataset Selection
## Breast Cancer Gene Expression Dataset (GSE42568)

### 1. Introduction
The purpose of this task is to identify a publicly accessible biological dataset, describe its source and scientific context, and formulate a research question. The selected dataset is hosted by the National Center for Biotechnology Information (NCBI) Gene Expression Omnibus (GEO).

### 2. Dataset identification
- Repository: NCBI Gene Expression Omnibus (GEO)
- Accession: GSE42568
- Organism: *Homo sapiens*
- Research area: Breast cancer genomics / gene-expression profiling
- Official record: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE42568

### 3. Dataset description
GSE42568 is a public gene-expression profiling dataset hosted by the NCBI Gene Expression Omnibus (GEO). It contains 121 human breast tissue samples, including 104 breast cancer biopsies and 17 normal breast tissue samples. The experiment uses the GPL570 platform (Affymetrix Human Genome U133 Plus 2.0 Array). The dataset is relevant to breast cancer genomics and transcriptomic research.

### 4. Dataset size
The GSE42568 dataset contains 121 samples: 104 breast cancer biopsies and 17 normal breast tissue samples. The experiment uses the GPL570 microarray platform. GEO sample expression tables contain 54,675 probe identifiers. These identifiers represent microarray probes, not necessarily 54,675 unique genes. Processed expression data are available through GEO sample records.

### 5. Proposed research question
**How do gene-expression patterns differ between breast cancer tissue samples and non-cancerous breast tissue samples in GSE42568?**

This is a proposed research question, not a result. No differential-expression analysis has been performed for this task.

### 6. Relevance to biotechnology and bioinformatics
The dataset is relevant to transcriptomics and cancer genomics. Public gene-expression datasets can be used in later computational workflows to learn sample annotation, data quality assessment, normalization, differential-expression analysis, visualization, and biological interpretation.

### 7. Proposed future workflow
1. Retrieve the processed expression matrix and sample metadata from GEO.
2. Confirm sample identities, group labels, and inclusion criteria.
3. Inspect the data and perform quality checks.
4. Use a suitable statistical workflow for the data type.
5. Correct for multiple testing and report effect sizes.
6. Interpret results using relevant biological databases and literature.

### 8. Limitations
This task is limited to dataset selection and documentation. It does not include laboratory work or original analysis. Group comparisons may be affected by clinical and technical confounders; these would need to be assessed before drawing conclusions.

### 9. Source
NCBI Gene Expression Omnibus. GSE42568. https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE42568

Clarke, C., Madden, S. F., Doolan, P., Aherne, S. T., Joyce, H., O'Driscoll, L., et al. (2013). Correlating transcriptional networks to breast cancer survival: A large-scale coexpression analysis. Carcinogenesis, 34(10), 2300–2308. https://doi.org/10.1093/carcin/bgt208⁠.

### 10. Conclusion
GSE42568 provides a public starting point for exploring breast-cancer-related gene-expression data. Documenting the accession, source, dataset structure, and a focused research question is the first step toward a reproducible bioinformatics project.
