# Radiogenomics
Repository hosting anonimised datasets and model objects for the paper "Integrated radiogenomics analyses allow for subtype classification and improved outcome prognosis of patients with locally advanced HNSCC"


The structure of the repository is as follows:
The repository is split into four subdirectories:

Data: hosts the datasets used (calculated ICCs, datasets for representatives for all three subdirectories and previous familiar versions to replicate models built under previous package versions other than the one that is being updated in CRAN). Scripts containing quality-of-life functions like spearman correlation clustering or thresholded probability metrics are included.

Subtypes: model and pooled data objects for all the reported models and performances for the subtypes.
Supplementation: model and pooled data objects for the GTV+log stat p90, GTV+metagenes, metagenes and GTV+log_stat_p90+metagenes.
Surrogates: model and pooled data objects for the six gene signature models.
