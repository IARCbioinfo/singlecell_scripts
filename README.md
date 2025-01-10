# singlecell_scripts
Python notebooks for MESOMICS2 single-cell analyses

Scripts follow the "Single-cell best practices" guide : Heumos, L., Schaar, A.C., Lance, C. et al. Best practices for single-cell analysis across modalities. Nat Rev Genet (2023). https://doi.org/10.1038/s41576-023-00586-w

scQC: Quality check for samples including low quality cell filtering, ambient RNA correction, and doublet detection

scNorm: Normalization of counts using shifted logarithm

scFeatSelec: Highly variable genes are flagged

scDimReduc: 2D UMAP coordinates computed for each sample

scClust: Clustering of cells using leiden community detection

scAnnot: Annotation of cell types using celltypist immune reference and numbat for tumor cells

01 ST_MESOMICS2 - Copy: Spatial analyses for visium data including quality check, normalization, squidpy analyses, and deconvolution using c2l
