# Comparative Coronavirus Genome Analysis

## Overview
University bioinformatics coursework project completed during my undergraduate studies while I was still a biology major.

This project explores comparative analysis of coronavirus genome sequences using Levenshtein distance as a string similarity metric. Publicly available viral genome data is processed, translated into amino acid sequences, and compared to measure relative sequence differences across samples.

The goal of the project is to demonstrate genome data processing and comparative techniques, not to establish biological causality or definitive conclusions about viral origins.

## Methodology
- Coronavirus genome sequences sourced from publicly available NCBI datasets
- RNA sequences translated into amino acid sequences
- Pairwise sequence similarity measured using Levenshtein distance
- Results visualized to compare relative differences across samples

## Results
Using Levenshtein distance as a similarity metric, pangolin-derived coronavirus sequences showed the lowest average edit distance to the SARS-CoV-2 reference within the limited dataset analyzed, with bat-derived sequences also showing relatively close similarity. Results reflect relative sequence similarity only and do not imply evolutionary origin or host attribution. The [full report](Report.pdf) has been made available here.

## Data Visualizations
### Minimum Mutation Analysis Table
![Minimum Mutation Analysis Table](https://user-images.githubusercontent.com/91595477/205288133-45c5e0f7-2816-46c5-86ff-dc9dc40b8e71.png)
*Figure 1: An Excel snapshot capturing the minimum number of mutations required for various coronaviruses to match the reference SARS-CoV-2 strain. The dataset includes five samples from each animal species tested, along with MERS and SARS for comparison, and five other SARS-CoV-2 variants.*

### Comparative Mutation Frequency Graph
![Comparative Mutation Frequency Graph](https://user-images.githubusercontent.com/91595477/205288069-233a7c10-4ac0-4d14-ba0e-d741635f4b66.png)
*Figure 2: A bar graph illustrating the comparative analysis of mutation frequencies. The graph compares the number of mutations across different coronaviruses, including samples from each animal species tested, relative to the reference SARS-CoV-2 strain.*

## Repository Contents
- `FASTAs/`: This directory contains FASTA files, which are formatted sequences of RNA genomes from various animal coronaviruses. All FASTA files have been found and extracted from the [National Center for Biotechnology Information (NCBI) database](https://www.ncbi.nlm.nih.gov/nuccore).
- `Project.py`: This script runs the core analysis. It facilitates the process of RNA translation into amino acids, aligns the genetic sequences, and calculates their differences.
- `Report.py`: This is the final write-up to conclude the project. The write-up includes a detailed summary of the experimental research, methods, and final conclusions, taking into consideration both the evidence gathered and the general consensus of the scientific community at the time.

## License
[MIT](LICENSE.txt)
