# Single-cell RNA-seq Analysis of Periodontitis (GSE174609)

## Objective

Investigate immune cell heterogeneity in peripheral blood mononuclear cells (PBMCs) associated with periodontitis using single-cell RNA sequencing and identify major immune populations through unsupervised clustering and marker-based annotation.

---

## Dataset

* Dataset: GSE174609
* Source: Gene Expression Omnibus (GEO)
* Data Type: Single-cell RNA sequencing (scRNA-seq)
* Sample Type: PBMC (Peripheral Blood Mononuclear Cells)

---

## Workflow

1. Data acquisition from GEO
2. Quality control (QC)
3. Normalization
4. Variable feature selection
5. Scaling
6. Principal Component Analysis (PCA)
7. UMAP dimensionality reduction
8. Louvain clustering
9. Marker gene identification
10. Cell type annotation

---

## Methods and Tools

* R
* Seurat
* Single-cell RNA-seq
* PCA
* UMAP
* Differential expression
* Bioinformatics

---

## Results

### Dataset Summary

* 7,710 cells analyzed
* 18,989 genes retained after preprocessing
* 13 immune populations identified

### Major Cell Types Identified

* Naive / Central Memory T cells
* Activated CD4 T cells
* Inflammatory Monocytes
* Cytotoxic NK / CD8 cells
* Monocytes
* Gamma Delta T cells
* B cells
* NK cells
* Dendritic cells
* Activated Monocytes
* Cycling cells
* Platelets

---

## Key Findings

* Successfully completed end-to-end scRNA-seq analysis workflow
* Identified diverse immune populations within PBMC samples
* Observed inflammatory monocyte-associated signatures
* Generated interpretable cluster-level marker profiles
* Produced publication-style visualizations

---

## Repository Structure

```text
figures/
├── annotated_umap.png
├── annotated_umap.pdf
├── marker_heatmap.png
└── sample1_umap.png

results/
├── all_cluster_markers.csv
├── cluster_markers.csv
├── cell_counts.csv
└── top10_markers.csv
```

---

## Outputs

* UMAP visualization
* Cluster annotations
* Marker gene tables
* Cell population summaries

---

## Reproducibility

Raw sequencing files are excluded from this repository and are available through GEO.

Dataset accession:
GSE174609

---

## Author

Prudhvi Teja Odela

Computational Biology · Bioinformatics · Single-cell Analysis

