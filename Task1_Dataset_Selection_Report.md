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

GSE42568 is a publicly available gene-expression profiling dataset hosted by the National Center for Biotechnology Information (NCBI) Gene Expression Omnibus (GEO).

The dataset contains gene-expression data from 121 human breast tissue samples:

- 104 breast cancer biopsy samples.
- 17 normal breast tissue samples.

The samples were analysed using the GPL570 Affymetrix Human Genome U133 Plus 2.0 Array platform.

The dataset provides an opportunity to study differences in gene-expression patterns between breast cancer and normal breast tissue.

Source: NCBI GEO – GSE42568
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE42568

### 4. Dataset size

The selected dataset contains the following information:

Dataset parameter| Verified value
Total samples| 121
Breast cancer samples| 104
Normal breast samples| 17
Microarray platform| GPL570
Number of probe identifiers per sample expression table| 54,675
Raw supplementary archive| 935.2 MB

Important clarification: The 54,675 entries represent microarray probe identifiers, not 54,675 unique genes. The dataset provides processed expression data within its GEO sample tables.

These values were checked against the official NCBI GEO record and associated sample data.

### 5. Proposed research question
**Can gene expression profiles distinguish breast cancer tissue samples from normal breast tissue samples using the publicly available GSE42568 dataset?**

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
