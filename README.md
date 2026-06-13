# Single-cell RNA-seq Analysis of Periodontitis (GSE174609)

## Objective

Investigate immune cell heterogeneity in peripheral blood mononuclear cells (PBMCs) associated with periodontitis using single-cell RNA sequencing.

## Dataset

GEO: GSE174609

## Workflow

* Data acquisition from GEO
* Quality control
* Normalization
* Variable feature selection
* PCA
* UMAP
* Louvain clustering
* Marker gene identification
* Cell type annotation

## Results

* 7,710 cells analyzed
* 18,989 genes retained
* 13 immune populations identified

## Major Cell Types

* Naive / Central Memory T cells
* Activated CD4 T cells
* Inflammatory Monocytes
* Cytotoxic NK / CD8 cells
* B cells
* Dendritic cells
* Platelets

## Technologies

R · Seurat · Single-cell RNA-seq · Bioinformatics

## Repository Structure

figures/ → publication-ready plots
results/ → processed outputs
scripts/ → reproducible analysis

Raw sequencing files are excluded and available through GEO.
