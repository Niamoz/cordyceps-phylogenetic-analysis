# cordyceps-phylogenetic-analysis

This project was completed as part of my undergraduate studies in Molecular Biology and Genetics.

The aim of the study was to investigate phylogenetic relationships among Cordyceps species and examine host-specific adaptations using sequence-based phylogenetic analysis.

## Tools Used

- MEGA
- MrBayes
- FigTree
- NCBI databases

## Project Content

This repository contains:

- Maximum Likelihood phylogenetic tree generated in MEGA
- Bayesian phylogenetic tree generated using MrBayes
- Preserved MrBayes analysis settings
- Summary of the phylogenetic analysis workflow
## Methods

Sequence data were obtained from NCBI databases and used for phylogenetic analysis of selected Cordyceps species.

Multiple sequence alignment was performed in MEGA. A Maximum Likelihood phylogenetic tree was then constructed in MEGA using 1,000 bootstrap replicates to evaluate branch support.

Bayesian phylogenetic inference was performed using MrBayes with a GTR substitution model (`nst=6`) and gamma-distributed rate variation among sites (`rates=gamma`). The analysis was run for 100,000 generations with four chains, sampling every 100 generations.

The resulting Bayesian phylogenetic tree was visualized in FigTree. Posterior probabilities were used to evaluate branch support in the Bayesian analysis.

## Results

### Maximum Likelihood Tree

![Maximum Likelihood Tree](max_likelihood.png)
The Maximum Likelihood phylogenetic tree was generated in MEGA. 
Node values represent bootstrap support.

### Bayesian Phylogenetic Tree

![Bayesian Phylogenetic Tree](bayesian.png)
The Bayesian phylogenetic tree was generated using MrBayes and visualized in FigTree. 
Node values represent posterior probability support.
