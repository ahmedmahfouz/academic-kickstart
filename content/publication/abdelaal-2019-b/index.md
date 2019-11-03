---
title: "A comparison of automatic cell identification methods for single-cell RNA sequencing data"
date: 2019-01-01
publishDate: 2019-11-03T15:14:42.016213Z
authors: ["Tamim Abdelaal", "Lieke Michielsen", "Davy Cats", "Dylan Hoogduin", "Hailiang Mei", "Marcel J. T. Reinders", "Ahmed Mahfouz"]
publication_types: ["2"]
abstract: "BACKGROUND Single-cell transcriptomics is rapidly advancing our understanding of the cellular composition of complex tissues and organisms. A major limitation in most analysis pipelines is the reliance on manual annotations to determine cell identities, which are time-consuming and irreproducible. The exponential growth in the number of cells and samples has prompted the adaptation and development of supervised classification methods for automatic cell identification. RESULTS Here, we benchmarked 22 classification methods that automatically assign cell identities including single-cell-specific and general-purpose classifiers. The performance of the methods is evaluated using 27 publicly available single-cell RNA sequencing datasets of different sizes, technologies, species, and levels of complexity. We use 2 experimental setups to evaluate the performance of each method for within dataset predictions (intra-dataset) and across datasets (inter-dataset) based on accuracy, percentage of unclassified cells, and computation time. We further evaluate the methods' sensitivity to the input features, number of cells per population, and their performance across different annotation levels and datasets. We find that most classifiers perform well on a variety of datasets with decreased accuracy for complex datasets with overlapping classes or deep annotations. The general-purpose support vector machine classifier has overall the best performance across the different experiments. CONCLUSIONS We present a comprehensive evaluation of automatic cell identification methods for single-cell RNA sequencing data. All the code used for the evaluation is available on GitHub ( https://github.com/tabdelaal/scRNAseq_Benchmark ). Additionally, we provide a Snakemake workflow to facilitate the benchmarking and to support the extension of new methods and new datasets."
featured: false
publication: "*Genome Biology*"
doi: "10.1186/s13059-019-1795-z"
---

