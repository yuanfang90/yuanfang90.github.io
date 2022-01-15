---
permalink: /research/
title: "Research Interest"
author_profile: true
redirect_from: 
  - /research/
  - /research.html
---

## Health Outcomes and Biomarkers

### Duchenne muscular dystrophy

[Duchenne muscular dystrophy (DMD)](https://www.parentprojectmd.org/about-duchenne/what-is-duchenne/about-duchenne-and-becker/) is X-linked, genetic disorder caused due to defects in the DMD gene, leading to abnormal dystrophin. 

* We modeled the variability in DMD persons disease trajectories, identified three groups of early age DMD motor trajectories, with the moderate progression group showing the largest steroid effect.
* We aim to build prognostic models on both natural history and clinical trial data for the DMD boys to predict future trajectories using statistical/machine learning algorithms.

### Dementia, cognitive impairment, and Alzheimer's disease 

Dementia is multifactorial in etiology. [Alzheimer's disease (AD)](https://www.cdc.gov/aging/aginginfo/alzheimers.htm), the most prevalent dementia, is characterized by proteinopathies (amyloid-beta peptide (A$\beta$), pathologic tau) and neurodegeneration.

* Aging immune cells:
  * We investigated association between immune-related biomarkers and cognitive aging outcomes, identified several easily obtained blood-based biomarkers and some protein biomarkers related to innate and adaptive immune cells that associated with worse cognitive testing performance, smaller total or regional brain volumes, and higher risk of incident dementia.
  * We are working on to identify circulating immune cell phenotypes in the pro-inflammatory and regulatory pathways that are risk factors for incident cognitive aging outcomes.
  * We aim to investigate whether the cognitive-outcome related immune cell phenotypes identified are associated with vascular factors known to increase susceptibility to cognitive aging.

* Cognitive trajectories:
  * We aim to model the heterogeneity and to identify patterns of cognitive trajectories across multiple domains.
  * We will use the comprehensive yet complex Neuropsycological testing measures as well as global factor measure for each cognitive domain using statistical/machine learning techniques. 
  * We aim to identify a more effective measure of cognitive function for each domain, in the sense that the subgroup of cognitive trajectories identified are more homogeneous and stable.
  * We will investigate the association between risk factors for incident cognitive aging outcomes and the subclasses identified.

## Statistical Learning

I develop new mixture models (and software) for cluster and classification analysis. Clustering can help with understanding which data observations are more similar to each other, and which are not. Data points similar to each other are grouped in a cluster together. Hence latent patterns or heterogeneity in the data can be revealed. I have a special interest in non-standard (non-Gaussian) data, specifically, compositional data. 

* One important example of compositional data is the microbiome taxa count data obtained from RNAseq. The absolute counts do not provide much information due to potential difference in sequencing depth. Hence, the microbime taxa count can only reveal relative abundance -- viewing it as a whole (or using a mathematical term as ``on a simplex'') makes more sense.
* We deveolop algorithms to cluster human microbiota composition: 
  * An R package has been developed to model and cluster microbiom data, which substantially lifted the heavy computational overhead in previous methods: [LNMVGA](https://github.com/yuanfang90/LNMVGA).
  * We are building mixture of regression models, hoping that other biomarkers could be taken into account when clustering microbiome data, so that we obtained more robust and more homogenous clusters.
  * We will extend the mixture of regression model to longitudinal settings so that change of micriobiom compositions can be model while patterns of changing trajectories could be studied.


