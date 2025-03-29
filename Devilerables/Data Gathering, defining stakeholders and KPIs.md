# Data Gathering, defining stakeholders and KPIs
## What is scRNAseq?
Single-cell RNA sequencing (scRNA-seq) is a powerful technique that allows to analyze gene expression at the individual cell level. Unlike traditional bulk RNA sequencing, which measures the average gene expression across a population of cells, scRNA-seq provides a high-resolution view of how genes are expressed in each individual cell. This technology has revolutionized our understanding of cellular diversity and gene regulatory networks, enabling researchers to uncover complex patterns of gene expression that drive cellular processes, development, and disease mechanisms. **scRNA-seq data typically consists of a matrix where rows represent individual cells and columns represent genes**, with each cell's gene expression measured by its RNA content.

## Data Acquisition 
For this project, we will use data publicly available, collected in Epiney, Morales and Dillon, 2025. However, this tool is optimized to use data obtained from any sources such as the Gene Expression Omnibus (GEO) or ArrayExpress. These datasets contain gene expression profiles of thousands of individual cells, with annotations for cell types, conditions, and possibly disease states. The ultimate goal is to use these datasets to train a computational model that can predict transcription factor (TF) activity in different cells based on their gene expression patterns. Applications can be, but are not limited to identifying relationships between transcription factors and their target genes, as well as studying how TFs regulate gene expression in different cellular contexts (e.g., cell types, diseases, or developmental stages).

Derek Epiney, Gonzalo N Morales Chaya, Noah R Dillon, Sen-Lin Lai, Chris Q Doe 2025 Transcriptional complexity in the insect central complex: single nuclei RNA-sequencing of adult brain neurons derived from type 2 neuroblastseLife14:RP105896
https://doi.org/10.7554/eLife.105896.1

## Stakeholder
* Researchers in Genetics and Molecular Biology: Interested in understanding gene regulation and transcription factor activity in various cellular contexts, such as disease models or developmental processes.

* Data Scientists and Bioinformaticians: Focused on developing models that can extract meaningful insights from high-dimensional scRNA-seq data, improving predictive power and accuracy in gene regulation studies.

* Medical Researchers: Looking to identify potential biomarkers and therapeutic targets related to transcription factors in diseases, such as cancer or neurodegenerative disorders.

* Pharmaceutical Companies: Potential users of the tool for drug discovery, aiming to identify how TFs might be targeted in the development of novel treatments.

* End Users (Research Laboratories and Academic Institutions): Scientists in academic labs who will use the final prediction tool to explore gene regulation and transcription factor activity in their own datasets.

## KPI
* 
