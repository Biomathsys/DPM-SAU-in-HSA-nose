# computational-modeling-of-microbial-communities-applied-to-D.-pigrum-and-S.-aureus-in-the-human-nose
This repository introduces the codes applied to the nasal microbial community of the latest available curated GEMs of D. pigrum and S. aureus. 

========================================

A metabolic modeling community of organisms D. pigrum and S. aureus in a nasal medium. 
This implements functionality to analyze the interaction between these two species within a human nose using different approaches to construct a community.

[![License (MIT Licence)](https://img.shields.io/badge/license-MIT-blue.svg?style=plastic)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/457820953.svg)](https://zenodo.org/badge/latestdoi/457820953)

----
*Authors*: [Reihaneh Mostolizadeh](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/systems-biology/team/dr-reihaneh-mostolizadeh/),
[Manuel Glöckler](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/systems-biology/team/)

To run it as a package, refer to: 

*Repository*: [https://github.com/manuelgloeckler/ncmw](https://github.com/manuelgloeckler/ncmw)

*Full documentaion page*: [https://manuelgloeckler.github.io/ncmw/](https://manuelgloeckler.github.io/ncmw/)



► Getting started with this repository
----------------------------

All codes can be run separately in the jupyter notebook.


Overview
--------

The repository has contained a folder named "Models," including models used in this work, a folder named "Media" including synthetic nasal medium (SNM3) used in this work and all other media created as a subset of SNM3, and all codes applied for the analysis in the related manuscript. 

**Model_Summary**

- **DP_SA_summatymodel_1**:
    gives an overview of both models used in this research
- **flux_distribution_SA**:
    is an overview of flux distribution of S. aureus 
- **flux_distribution_DP**
    is an overview of flux distribution of D. pigrum 
- **creat_compm_media**
    the COMPM media was created  
    
 **Similarity** 
  
- **jaccard_index**:
    which computed the similarity between both species 
- **uptake_sekeration_inverstigation**: 
    compare the similarity between both species from the perspective of uptake and secretion metabolites

 **Community** 

- **number_12** the analysis of the community based on the pooled approaches
       
- **number_13** the analysis of the community based on the integrated approaches while we have media SNM3, exchange, COMPM
        
- **number_14** the analysis of the community based on the shuttle approaches while we have media SNM3, exchange, COMPM (shuttle environment was considered as all 111 total exchange reactions)- linear combination of the objective function was implemented.
 
- **number_16** the analysis of the community based on the shuttle approaches while we have media SNM3, exchange, COMPM (shuttle environment was considered as all 111 total exchange reactions)- the convex combination of the objective function was implemented.

- **number_18** the analysis of the community based on the shuttle approaches while we have media SNM3, exchange, COMPM (shuttle environment was considered as all uptake and secreted metabolites)- linear combination of the objective function and convex combination were implemented.
 
- **numbers_20-21-22-23-24-25** computing the COOPM media in different scenarios and the analysis of the community in COOPM in all different conditions.

- **numbers_26-28** a brief analysis of different scenarios while the community was created as a package to be called.

☮ Licensing and distribution
----------------------------

The University of Tübingen, Germany

