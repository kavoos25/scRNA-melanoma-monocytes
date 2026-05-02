# 🧬 Single-Cell RNA-seq Analysis of Melanoma Monocytes

### *Reproducible Pipeline with Offline GSEA & Publication-Ready Figures*

---

## 🎯 Project Summary

This project presents a complete and reproducible **single-cell RNA sequencing (scRNA-seq)** analysis workflow focused on **melanoma-associated monocytes**.

It integrates advanced transcriptomic analysis with a **fully offline Gene Set Enrichment Analysis (GSEA)** pipeline, designed to work in restricted or low-connectivity environments.

---

## 🔬 Scientific Objectives

* Characterize transcriptional heterogeneity of monocyte populations
* Identify biologically meaningful clusters
* Reveal functional pathways using GSEA (KEGG, GO, Reactome)
* Generate publication-quality visualizations

---

## 🚀 Key Contributions

✅ End-to-end scRNA-seq pipeline using Scanpy
✅ Robust differential expression analysis
✅ **Offline GSEA implementation (custom GMT parsing & validation)**
✅ Multi-source pathway analysis (KEGG, GO, Reactome)
✅ Automated figure generation (publication-ready)
✅ Reproducible and modular notebook structure

---

## 📊 Highlight Results

### 🔹 Final Multi-panel Figure

![Final Figure](figures/260430-melanoma-monocytes/85-260430-melanoma-monocytes_FINAL_multi_panel.png)

---

## 🧪 Biological Insights

* **Cluster 0**: Enriched in translation and ribosomal pathways
  → Indicates high biosynthetic and metabolic activity

* **Cluster 8**: Enriched in immune and viral-response pathways
  → Suggests activated or inflammatory monocyte subtype

* Overall results highlight **functional heterogeneity of tumor-associated monocytes**

---

## 🧠 Technical Highlights

This project demonstrates strong capabilities in:

* Bioinformatics pipeline design
* Data preprocessing and QC (Scanpy)
* High-dimensional data analysis
* Gene set enrichment analysis (GSEApy)
* Data visualization (Matplotlib, Seaborn)
* Debugging and optimization of real-world datasets
* Working in offline/restricted computational environments

---

## 📁 Project Structure

```
notebooks/       → step-by-step analysis pipeline
resources/       → offline gene sets (GMT files)
results/         → processed outputs (CSV)
figures/         → publication-quality figures
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run notebooks sequentially:

```
01 → preprocessing  
02 → clustering  
03 → marker detection  
...  
07 → GSEA analysis  
```

---

## 💡 Reproducibility

* Fully reproducible pipeline
* Offline-compatible GSEA (no internet required after setup)
* Clean modular structure for reuse in other datasets

---

## 🎓 Research & Collaboration

I am actively seeking:

* Postdoctoral research opportunities
* Short-term research collaborations
* Bioinformatics and data analysis projects

---

## 📬 Contact

**Kavoos Momeni**
PhD in Molecular Genetics & Bioinformatics

* Email: kavoosmomeni@gmail.com
* LinkedIn: Kavoos Momeni

---

## ⭐ If you find this project useful

Please consider starring the repository to support further development.

---

