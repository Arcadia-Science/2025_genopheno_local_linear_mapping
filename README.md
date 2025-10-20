# A quantitative-genetic decomposition of a neural network

This code repository contains or points to all materials required for creating and hosting the publication entitled, *A quantitative-genetic decomposition of a neural network*.

The publication is hosted at [this URL](https://research.arcadiascience.com/pub/method-qg-nn-decomposition).

## Data Description

This repository contains simulated genotype-phenotype mapping data used to demonstrate the application of Equivalent Linear Mapping (ELM) to deep learning models in genomic prediction. The dataset includes 10,000 haploid individuals, each with 64 biallelic loci expressing 5 quantitative traits that range from purely additive (Trait 1) to highly epistatic (Trait 5). Each trait is controlled by additive effects at all loci plus 32 pairwise epistatic interactions, with all loci maintained at 50/50 allele frequencies and no linkage disequilibrium. Data were previously generated using AlphaSimR [Gaynor et al., 2021](https://academic.oup.com/g3journal/article/11/2/jkaa017/6025179) as part of a larger study on scaling behavior of neural networks in genomic prediction [Sandler and York, 2025](https://research.arcadiascience.com/pub/result-gp-deep-learning-scaling/release/1/).

## Reproduce

Please see [SETUP.qmd](SETUP.qmd).

## Contribute

Please see [CONTRIBUTING.qmd](CONTRIBUTING.qmd).
