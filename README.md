# 📘 HIV Gene Expression Analysis: SAHA vs DMSO (PCA & t-SNE Visualization)
🔬 Project Overview

This project presents an exploratory analysis of gene expression data comparing HIV-infected and non-infected human cell lines treated with three compounds: SAHA, PMA, and DMSO. Our objective is to understand how these treatments affect gene expression patterns, with a specific focus on uncovering biological variation and identifying potential batch effects prior to differential expression analysis.

We apply two widely used dimensionality reduction techniques in computational biology — Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) — to reduce high-dimensional transcriptomic data into low-dimensional space that can be visualized and interpreted.

📁 Dataset Context

The dataset includes gene expression profiles under the following conditions:

    Treatment groups: SAHA, PMA, and DMSO

    Infection status: HIV-infected vs non-infected

    Replicates and potential batch differences

This data allows us to explore how latent HIV reservoirs might be reactivated through epigenetic modulators like SAHA, which is of particular interest in HIV cure research.

🧠 Goals

    Visualize the major sources of variation across samples using PCA

    Identify clusters or separation patterns between treatment and infection groups

    Explore whether there are batch effects that need to be addressed before downstream analysis

    Practice applying dimensionality reduction techniques in R with real biological data

    Build a foundation for future differential expression analysis using tools like DESeq2 or edgeR

⚙️ Methods & Tools

The project was developed entirely in R, using the following key libraries:

    ggplot2 – data visualization

    Rtsne – t-SNE dimensionality reduction

    dplyr – data manipulation

    DESeq2 – normalization and exploratory analysis (optional/future use)

    readr, tibble – data loading and wrangling

✨ Techniques applied:

    Principal Component Analysis (PCA) to detect variance structure in the gene expression matrix

    t-SNE to capture local sample relationships in a non-linear manner

    Data cleaning and preprocessing steps (filtering, normalization, etc.)

    Color-coded plots by infection status, treatment group, and replicate batch

👥 Authors

    Luis Carlos Ospina 

    Pau Ribera 

    Nicolás Costa

Project completed as part of coursework in the Bioinformatics Bachelor's Degree at the Polytechnic University of Catalonia (UPC), focusing on transcriptomic analysis and dimensionality reduction.

📊 Results

Preliminary visualizations suggest that:

    Treatment effects (especially PMA and SAHA) generate distinguishable expression patterns

    Some degree of clustering based on HIV infection status is observable

    Potential batch effects may influence separation in t-SNE plots, warranting normalization or batch correction in downstream steps

Note: these observations are exploratory and should be confirmed via formal statistical testing in a future pipeline.


📎 License & Citation

This repository is educational and open for learning purposes. If you find it useful, feel free to reference it or adapt it for your own academic projects.
