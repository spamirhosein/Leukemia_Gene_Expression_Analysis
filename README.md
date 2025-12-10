# Leukemia Gene Expression Analysis

This project analyzes gene expression data from Acute Myeloid Leukemia (AML) patients compared to normal bone marrow controls.

## Goals
- Identify differentially expressed genes between AML and Normal tissue.
- Visualize sample clustering using PCA.
- Highlight key marker genes (e.g., HOXA9).

## Dataset
- **Source:** [Kaggle: Leukemia Gene Expression (CUMIDA)](https://www.kaggle.com/datasets/brunogrisci/leukemia-gene-expression-cumida)
- To download the dataset, configure your Kaggle API as per Kaggle’s docs or manually download the CSV and place it in data/.
- **Samples:** 60 samples (AML, Bone Marrow, PB, CD34+)
- **Features:** ~22,000 genes (Affymetrix Microarray)

## Key Findings
- **PCA:** Clear separation between AML and Normal controls based on gene expression profiles.
- **Marker Discovery:** Identified **HOXA9** (Probe 214651_s_at) as the top upregulated gene in AML (Log2FC > 3.0, P < 1e-5), consistent with known literature on leukemogenesis.

## Tools Used
- Python (Pandas, NumPy)
- Scipy (T-tests)
- Matplotlib/Seaborn (Volcano Plots, PCA)
