---
permalink: /research/
title: "Research"
author_profile: true
---

## Application Fields

### Dementia, cognitive impairment, and Alzheimer's disease 

Dementia is multifactorial in etiology. [Alzheimer's disease (AD)](https://www.cdc.gov/aging/aginginfo/alzheimers.htm), the most prevalent dementia, is characterized by proteinopathies (amyloid-beta peptide (A$\beta$), pathologic tau) and neurodegeneration. Along with a multidisciplinary research team led by [Dr. Lunetta](https://www.bu.edu/sph/profile/kathryn-lunetta/) and [Dr. Murabito](https://www.bumc.bu.edu/busm/profile/joanne-murabito/), we are working on the following projects in the [Framingham Offspring Study (FHS)](https://framinghamheartstudy.org/).

* Aging immune cells:
  * We investigated association between immune-related biomarkers and cognitive aging outcomes, identified several easily obtained blood-based biomarkers and some protein biomarkers related to innate and adaptive immune cells that associated with worse cognitive testing performance, smaller total or regional brain volumes, and higher risk of incident dementia.
  * We identified circulating immune cell phenotypes in the pro-inflammatory and regulatory pathways that are risk factors for incident cognitive aging outcomes.

* Cognitive trajectories:
  * We modeled the heterogeneity and to identify patterns of cognitive trajectories across multiple domains.
  * We will investigate the association between risk factors for incident cognitive aging outcomes and the subclasses identified.

### Duchenne muscular dystrophy

[Duchenne muscular dystrophy (DMD)](https://www.parentprojectmd.org/about-duchenne/what-is-duchenne/about-duchenne-and-becker/) is X-linked, genetic disorder caused due to defects in the DMD gene, leading to abnormal dystrophin. I joined [Dr. Utkarsh Dang](https://sites.google.com/view/utkarshdang/home?authuser=0)'s research team on modeling DMD progression heterogeneity prior my post-doc training started, acted as a research assistant and data analyst. The collaboration with Dr. Dang's team is still ongoing.

* We modeled the variability in DMD persons disease trajectories, identified three groups of early age DMD motor trajectories, with the moderate progression group showing the largest steroid effect.
* We aim to build prognostic models on both natural history and clinical trial data for the DMD boys to predict future trajectories using statistical/machine learning algorithms.


## Statistical Learning

I develop new mixture models (and software) for cluster and classification analysis. Clustering can help with understanding which data observations are more similar to each other, and which are not. Data points similar to each other are grouped in a cluster together, hence latent patterns or heterogeneity in the data can be revealed. I have a special interest in non-standard (non-Gaussian) data, specifically, compositional data. 

* One important example of compositional data is the microbiome taxa count data obtained from RNAseq. The absolute counts do not provide much information due to potential difference in sequencing depth. Hence, the microbime taxa count can only reveal relative abundance -- viewing it as a whole (or using a mathematical term as "on a simplex") makes more sense.
* We deveolop algorithms to cluster human microbiota composition: 
  * An R package has been developed to model and cluster microbiom data, which substantially lifted the heavy computational overhead in previous methods: [LNMVGA](https://github.com/yuanfang90/LNMVGA).
  * We built mixture of regression models, hoping that other biomarkers could be taken into account when clustering microbiome data, so that we obtained more robust and more homogenous clusters.
  * We are extending the modeling of the latent variable to a multivariate t distribution to handel outliers.
  * We will extend the mixture of regression model to longitudinal settings so that change of micriobiom compositions can be model while patterns of changing trajectories could be studied.


