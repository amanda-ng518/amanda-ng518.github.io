---
title: "Transit and Crime: Investigating Assault Clusters Around Toronto’s TTC Subway Lines"
excerpt: '<p><i>Fall 2024 STA465 Course Project </i></p>'

collection: portfolio
---
This study investigates the spatial distribution of assault incidents in Toronto in 2023, with a focus on the potential clustering of assaults near Toronto Transit Commission (TTC) subway routes. Utilizing assault occurrence data from the Toronto Police Service and TTC subway route, a spatial analysis was conducted to determine whether proximity to subway infrastructure influences the intensity and clustering of assault incidents.

In this study, we create different buffers around subway routes and classified incidents as occurring near or away from subway routes accordingly. In other words, we define the idea of “near TTC subway routes” using different buffer sizes. Preliminary findings indicated that 51.3% of assaults occurred within the 1km buffer, with higher densities observed near Line 1 and Line 2 routes compared to Lines 3 and 4. The study employs point pattern analysis and spatial modeling, including testing of complete spatial randomness, kernel density estimation, point process modelling, cluster detection through HDBSCAN, to evaluate spatial dependence.

The spatial analysis of Toronto assault cases reveals significant clustering patterns, rejecting the null hypothesis of complete spatial randomness (CSR) across all tests. Kolmogorov-Smirnov tests and Ripley’s K-function demonstrate significant clustering of assault cases in Toronto and degree of clustering depends on whether the assault occurred within the TTC subway route buffer (i.e. near TTC subway). Comparison of Ripley’s K-function on different within buffer subsets reveals that clustering patterns depend on the buffer size as well (i.e. proximity to TTC subway route). Clustering analysis on different data subsets through HDBSCAN shows that assault incidents near TTC subway routes remain concentrated within 1-2 km buffers and retain their spatial patterns when expanded to 5 km and the entire city. Larger datasets revealed additional smaller clusters, suggesting that TTC subway routes may influence the distribution of assault incidents.

Research findings can provide insights for urban planners and policymakers, informing strategies to enhance public safety around transit infrastructure. This research contributes to understanding the interplay between urban crime patterns and public transit systems, with implications for cities beyond Toronto.

Click [final report](https://github.com/amanda-ng518/amanda-ng518.github.io/blob/master/files/Transit%20and%20Crime.html) to view more.
