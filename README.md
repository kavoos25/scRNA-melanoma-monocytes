# 🧬 scRNA-seq Analysis of Melanoma Monocytes

## 📌 Overview

This project presents a full single-cell RNA sequencing (scRNA-seq) analysis pipeline for melanoma-associated monocytes.

It includes preprocessing, clustering, marker detection, and a fully offline Gene Set Enrichment Analysis (GSEA) pipeline.

---

## 🚀 Key Features

* Complete scRNA-seq workflow (Scanpy-based)
* Differential gene expression analysis
* Offline GSEA (KEGG, GO, Reactome)
* Publication-ready visualizations
* Reproducible and modular pipeline

---

## 📊 Final Results

### 🔹 Multi-panel Figure

![Final Figure](figures/83-260430-melanoma-monocytes_FINAL_multi_panel.png)

---

## 🧪 Biological Insight

* Cluster 0 shows enrichment in translation and ribosomal activity
* Cluster 8 highlights immune and viral response pathways
* Indicates functional heterogeneity in monocyte populations

---

## 📁 Project Structure

```
notebooks/       → analysis pipeline
resources/       → offline gene sets (GMT)
results/         → processed outputs
figures/         → publication figures
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run notebooks step by step:

```
01 → preprocessing
02 → clustering
...
07 → GSEA analysis
```

---

## 📬 Author : kavoosmomeni@gmail.com

Kavoos Momeni
Molecular Genetics & Bioinformatics

---
