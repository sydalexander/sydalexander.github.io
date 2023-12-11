---
title: "The Trials and Tribulations of Reproducing the Malcomb Study"
excerpt_separator: "<!--more-->"
categories:
  - Lab
tags:
  - Vulnerability
  - GIS
  - Malawi
  - Reproduction
---
Coming into this study, there were already many decisions Malcomb made that I felt a little skeptical about. For one, the interviews were an integral part in determining the weights for different variables and indicators for the study, yet the methods by which Malcomb determines the weights are not clearly laid out in his methodology. Thinking about Tate's framework, Malcomb's weighting strategy was normative and deductive, however, we are not privvy to the exact theories which Malcomb's "experts" are making in order to determine weights. 

I also thought that Malcomb's original visualization for climate vulnerability scores didn't make much sense; I understand that it was likely in raster form because the inputs (eg. flooding) were originally rasters, but to me this didn't seem like the most effective way to depict vulnerability. Instead, I created a new map visualizing the mean vulnerability scores for each TA, which would be geographical units easier to implement changes into, rather than ambigious areas in a raster. TAs are discrete. Within Tate's framework, this poses an issue with analysis scale (Tate, 2013). TAs are a unit in which Malcomb conducts part of his analysis, but he is not consistent in using them throughout his study. For example, Average Relisilience Scores are depicted in TAs, but their vulnerability model is a raster and not broken up into TAs. If TAs are discrete administrative units in which policy can be implemented, then it makes more sense to visualize vulnerabiltiy using TAs (Malcomb et al., 2014). 

**References**

Malcomb, D. W., E. A. Weaver, and A. R. Krakowka. 2014. Vulnerability modeling for sub-Saharan Africa: An operationalized approach in Malawi. Applied Geography 48:17–30. DOI:10.1016/j.apgeog.2014.01.004

Tate, E. 2013. Uncertainty Analysis for a Social Vulnerability Index. Annals of the Association of American Geographers 103 (3):526–543. DOI:10.1080/00045608.2012.700616.

[Check out my contributions to the study here](https://sydalexander.github.io/RPr-Malcomb-2014/)

[Link to the GitHub repository](https://github.com/sydalexander/RPr-Malcomb-2014)
