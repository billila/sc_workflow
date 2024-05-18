# sc_workflow

## Introduction 
With the exponential growth in the size and complexity of single-cell RNA-seq data, traditional workflows are becoming increasingly computationally intensive. Existing tools often need help to efficiently handle such large datasets, frequently running out of memory. To address this challenge, the adoption of more efficient algorithms and out-of-memory data representations is crucial for effective analysis. This study presents a comprehensive comparison of workflows for single-cell data analysis, evaluating their performance and efficacy within R and Python programming environments. We assess the capabilities of Seurat and Bioconductor in R, and Scanpy and rapids_singlecell in Python, with a focus on their utilisation of both Central Processing Units (CPUs) and Graphics Processing Units (GPUs) for optimising computational efficiency. Real single-cell RNA-seq datasets  are used to assess workflow scalability.

## Dataset
Real single-cell RNA-seq datasets, including approximately 1.3 million cells (1.3M) from the mouse brain , BE1 a benchmark dataset providing a controlled heterogeneity environment , sc_mixology (sc_mix) dataset is a collection of single-cell RNA sequencing (scRNA-seq) data from cell line mixtures, and CITE-seq cord blood (cb) dataset that captures both transcriptomic and proteomic information at the single-cell level, are used to assess workflow scalability. 

## Workflow for Large single-cell RNA-seq data in Bioconductor
To guide the user in the pipeline setting in the Bioconductor framework we also provide a vignette featuring the most efficient methods regarding scalability, computational time, and memory usage developed, serving as a valuable resource for researchers working with large single-cell RNA seq data.

Workflow for Large single-cell RNA-seq data in Bioconductor: https://htmlpreview.github.io/?https://github.com/billila/sc_workflow/blob/main/large_sc_workflow.html

