An important step for analysis of [[RNA-seq]] data

### Quality control tools
There are several tools that can be used for this purpose:
- 2012_Wang: **RseQC**
- 2012_DeLuca **RNA-SeQC**
- 2012_Garcia-Alcalde **Qualimap**
- 2014_Guo **GC3**
- 2015_Hartley **QoRTs**
- 2018_Zhou: **RNA-QC-chain** https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-4503-6
- 2020_Kumar: **iSeqQC** https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-3399-8 ^5f39ed

### Quality metrics
There are multiple metrics to assess:
- Per base sequencing quality averaged
- Mapping statistics (% mapped vs unmapped)
- Percentage of reads mapped uniquely to human genome (no contamination of libraries)
- Average mapping quality (outliers)
- Coverage uniformity over gene body for all samples
- Normalized expression of housekeeping genes
- GC bias plot
- Unsupervised PCA clustering (un-normalized or z-scored normalized)
- Pearson correlation 
- Hierarchical relationship (phenotypic clustering) 

Source: [[RNA-seq quality control#^5f39ed]]

### Factors that influence quality of RNA-seq data
Causes that may change the quality of RNA-seq data:
- Most [[Fixative methods]] are not useful since RNA can crosslink to proteins and therefore reduce data quality although there are **exceptions**.