---
permalink: /research/
title: "Research"
author_profile: true
---

## Statistical Learning

I develop new mixture models (and software) for cluster and classification analysis. My past and current interest is in non-standard (non-Gaussian) data, specifically, compositional data. In the future, I plan to evaluate and develop tools for modeling longitudinal data and integrating data obtained from multiple sources (multi-omics).

* One important example of compositional data is the microbiome taxa count data obtained from RNAseq. The absolute counts do not provide much information due to potential differences in sequencing depth. Hence, the microbiome taxa count can only reveal relative abundance -- viewing it as a whole (or using a mathematical term as "on a simplex") makes more sense.
* We develop algorithms to cluster human microbiota composition using logistic normal multinomial (LNM) models and its extensions: 
  * An R package has been developed to model and cluster microbiome data, which substantially lifted the heavy computational overhead in previous methods: [LNMVGA](https://github.com/yuanfang90/LNMVGA).
  * We built mixtures of regression models, hoping that other biomarkers could be taken into account when clustering microbiome data so that we obtained more robust and homogenous clusters.
  * We have extended the modeling of the latent variable to a multivariate *t* distribution to handle outliers.
  * We are extending the mixture of LNM models to matrix-variate normal so that time-coursed microbiome composition can be modeled.
 
* Future research will focus on developing clustering algorithms that can identify distinct patterns in longitudinal trajectories, including the detection of heterogeneous change points.
  * We will extend the latent class mixed model (LCMM) to the finite mixture of logistic normal multinomial regression models framework, specifically for clustering discrete longitudinal data such as microbiome relative abundance and compositional data.
  * We will explore models such as Gaussian Process Regression and semi-hidden Markov models to confirm their ability to detect heterogeneous change points in time-series discrete data, allowing for the identification of individual-specific trajectory changes in disease progression.
  * We plan to develop models capable of clustering sample trajectories into sub-groups while simultaneously detecting group-specific change points.
 
## Application Fields

### Dementia, cognitive impairment, and Alzheimer's disease 

Dementia is multifactorial in etiology. [Alzheimer's disease (AD)](https://www.cdc.gov/aging/aginginfo/alzheimers.htm), the most prevalent dementia, is characterized by proteinopathies (amyloid-beta peptide, pathologic tau) and neurodegeneration. 

My collaborator Dr. [Jayoung Han](https://www.fdu.edu/profiles/jayoung116_han/) and I are working on investigating the role of medication adherence, a novel non-invasive biomarker that is already a part of pharmacists' daily practice, as an effective predictor for early cognitive decline and developing predictive models that incorporate immigration status, medication adherence, and cognitive outcomes using publicly available data from the Health and Retirement Study. This work aims to provide equitable healthcare solutions by enhancing model sensitivity for different demographic groups. 

### Duchenne muscular dystrophy

[Duchenne muscular dystrophy (DMD)](https://www.parentprojectmd.org/about-duchenne/what-is-duchenne/about-duchenne-and-becker/) is an X-linked, genetic disorder caused due to defects in the DMD gene, leading to abnormal dystrophin. I joined Dr. [Utkarsh Dang](https://sites.google.com/view/utkarshdang/home?authuser=0)'s research team on modeling DMD progression heterogeneity prior my post-doc training started, acted as a research assistant and data analyst. I am currently actively collaborating with Drs. [Utkarsh Dang](https://sites.google.com/view/utkarshdang/home?authuser=0), [Melissa Moraless](https://www.binghamton.edu/pharmacy-and-pharmaceutical-sciences/academics/departments/pharmaceutical-sciences/profile.html?id=mmorales), and [Eric Hoffman](https://www.binghamton.edu/pharmacy-and-pharmaceutical-sciences/academics/departments/pharmaceutical-sciences/profile.html?id=ehoffman) on multiple projects in DMD research.

* We modeled the variability in DMD persons disease trajectories, and identified three groups of early-age DMD motor trajectories, with the moderate progression group showing the largest steroid effect.
* We studied how specific *DMD* gene mutations affect baseline and longitudinal changes in clinical outcomes.
* We are investigating lipidomic dynamics in DMD by looking at the differential expression and treatment responses among lipid species in the ceramide pathways.
* We will explore lipid-protein-phenotype interactions integrating the lipidomic, proteomic, and clinical motor function outcomes data.
* We will stratify the multi-omics data by specific genetics modifiers to elucidate the molecular pathways under the disease progression.
* We will use the holistic multi-omics information to identify novel therapeutic targets for potential drug repurposing and combined therapies.

