# Single-cell RNA-seq Analysis of Periodontitis (GSE174609)

## Objective

Investigate immune cell heterogeneity in peripheral blood mononuclear cells (PBMCs) associated with periodontitis using single-cell RNA sequencing and identify immune populations through unsupervised clustering and marker-based annotation.

---

## Dataset

Source: GEO — GSE174609

Single-cell RNA sequencing dataset generated from PBMC samples.

### Study Design

Samples included:
- Periodontitis
- Post-treatment
- Healthy controls

Total samples included: 22

Analysis focused on characterizing immune cell composition and cellular heterogeneity across PBMC samples.

---

## Workflow

1. Data acquisition from GEO  
2. Quality control (QC)  
3. Data normalization  
4. Variable feature selection  
5. Data scaling  
6. Principal Component Analysis (PCA)  
7. UMAP dimensionality reduction  
8. Graph-based Louvain clustering  
9. Marker gene identification  
10. Cell type annotation  

---

## Methods and Tools

- R
- Seurat
- Single-cell RNA sequencing
  (scRNA-seq)
- PCA
- UMAP
- Differential expression analysis
- Bioinformatics

---

## Results

### Dataset Summary

- 22 PBMC samples analyzed (Periodontitis, Post-treatment, Healthy controls)
- 7,710 high-quality cells retained after quality control
- 18,989 genes retained for downstream analysis
- 13 transcriptionally distinct immune populations identified

### Annotated Cell Populations

- Naive / Central Memory T cells
- Activated CD4 T cells
- Inflammatory Monocytes
- Cytotoxic NK / CD8 cells
- Monocytes
- Gamma Delta T cells
- B cells
- NK cells
- Dendritic cells
- Activated Monocytes
- Cycling cells
- Platelets

### Key Findings

- Characterized immune cell heterogeneity across PBMC samples
- Identified distinct immune populations through unsupervised clustering
- Observed inflammatory monocyte-associated transcriptional signatures
- Generated cluster-specific marker gene profiles
- Produced interpretable UMAP and marker heatmap visualizations

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

- UMAP visualization
- Cluster annotation
- Marker gene tables
- Cell population summaries

---

## Reproducibility

Raw sequencing files are excluded from this repository and are publicly available through GEO.

Dataset accession:
GSE174609

---

## Author

Prudhvi Teja Odela

Bioinformatics · Computational Biology· Single-cell Transcriptomics
