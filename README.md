# awesome-complex-trait-genetics

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of awesome tools for human complex trait genetics, biased/slanted towards post-GWAS analysis.

How can you add your tool? via a pull request, if you dont know what that is, read the contributing guidlines: (https://github.com/MichelNivard/awesome-genetics/blob/main/contributing.md)

**This list may for the basis for a static review**, in which case serious contributors, so those who contribute to the list and to the preamle paragraphs for each section, will be ivited as collaborators.


## genetic architecture

- [LDSC](https://github.com/bulik/ldsc) ldsc is a python command line tool for estimating heritability and genetic correlation from GWAS summary statistics. ldsc also computes LD Scores.
- 

### Univariate models (heritability/poligenicity/stratified etc)

- [i-LDSC](https://github.com/lcrawlab/i-LDSC)   interaction-LD score (i-LDSC) regression: Model an additional score that measures the amount of non-additive genetic variation that is tagged by each variant in the data.
- [ACLR](https://github.com/arminschoech/ACLR) Autocorrelation LD regression: a tool to efficiently estimate the autocorrelation of latent effects in large genetic data sets. (WARNING Python 2.7 code)


## Genetic correlation (LD score and derivatives)


- [HDL](https://github.com/zhenin/HDL) High-Definition Likelihood (HDL) is a likelihood-based method for estimating genetic correlation using GWAS summary statistics. Compared to LD Score regression (LDSC), It reduces the variance of a genetic correlation estimate by about 60%.




### Stratified/local genetic correlatons

- [LAVA](https://github.com/josefin-werme/LAVA) LAVA (Local Analysis of [co]Variant Association) is a tool developed for local genetic correlation (rg) analysis.

### Ancestry aware Genetic correlations:

- [s-ldxr](https://github.com/huwenboshi/s-ldxr) S-LDXR is a method to stratify squared trans-ethnic genetic correlation by genomic annotations from GWAS summary statistics.

## Model trait relationships

### Genetic SEM/Factor models

- [GenomicSEM](https://github.com/GenomicSEM/GenomicSEM) R package for Genomic Structural Equation Models. user defined models of the relation between complex traits based on GWAS summary data.


### two sample Mendelian randomisation

-[TwoSampleMR](https://github.com/MRCIEU/TwoSampleMR) An R package for performing Mendelian randomization using GWAS summary data.

### Mendelian randomisation/Genetic arhitecture hybrids

-[lhcMR](https://github.com/LizaDarrous/lhcMR) lhcMR is an R package that performs bi-directional causal estimation between a pair of traits, while accounting for the presence of a potential heritable confounder acting on the pair.
-[CAUSE](https://github.com/jean997/cause)
-[LCV](https://github.com/lukejoconnor/LCV) LCV is an LD score based method for inferring genetically causal relationships using GWAS data.

## Colocalisation of causal varianta 

- [coloc](https://github.com/chr1swallace/coloc) R package to perform genetic colocalisation analysis, test whether two related phenotypes share common genetic causal variant(s) in a given region.




##

## Simulation

- [GWASBrewer](https://github.com/jean997/GWASBrewer) A flexible tool for simulating realistic GWAS summary statistics for one, or many, traits.

## Genomic data wrangling

- [bigsnpr](https://github.com/privefl/bigsnpr) R package for the analysis of massive SNP arrays, primarily designed for human genetics.
- [ukbrapR](https://github.com/lcpilling/ukbrapR) ukbrapR (phonetically: 'U-K-B-wrapper') is an R package for working in the UK Biobank Research Analysis Platform (RAP). The aim is to make it quicker, easier, and more reproducible.
- [MungeSumstats](https://github.com/Al-Murphy/MungeSumstats) R package designed to facilitate the standardisation of GWAS summary statistics.
