---
title: "Reflecting on the Kang Study"
excerpt_separator: "<!--more-->"
categories:
  - Lab
tags:
  - COVID-19
  - GIS
  - Spatial Accessibility
  - Reproduction
---
With the Kang study, we continued to work with Python, which is a new programming language to me. I gained more familiarity reading Python syntax and working in this new computing environment. This was also my first time working remotely through super computers using CyberGISX; there was definitely a learning curve with setting it up and connecting it to GitHub. Efficiency was a big concern of ours while working through this study given that we were working with such large data sets; several steps or functions took relatively long times to run. By working through the reproduction study, I learned more about different modules, such as the osmnx modules, and how to impelement them.
In this vein, I also improved my troubleshooting abilites by reading through code documentation, and putting in my own data.

Our primary modification to this study involved using the **osmnx.speed** module, replacing several for loops that originally calculated speed limits of raods. This change simplified the code, improving both its legibility and its effiency. Something else we attempted to improve upon in the code was to improve translation from hospital catchments into hexagons by revising the **overlap_calc** function. Although we were unable to accomplish this, it would still be something worth revising in the future. The scope of this study and reanalysis focused specifically on Illinois; it may be worth applying the methods of this study to other states, especially states neighboring Illinois.

**References**

Kang, J. Y., A. Michels, F. Lyu, Shaohua Wang, N. Agbodo, V. L. Freeman, and Shaowen Wang. 2020. Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA. International Journal of Health Geographics 19 (1):1–17. DOI:10.1186/s12942-020-00229-x.

[Check out my contributions to the study here](https://sydalexander.github.io/RPr-Kang-2020/)

[Link to the GitHub repository](https://github.com/sydalexander/RPr-Kang-2020)
