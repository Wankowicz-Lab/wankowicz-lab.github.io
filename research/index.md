---
title: Research in the Wankowicz Lab
layout: default
group: research
---


<br>
<br>

## The lab has two main areas of research


1. Developing software to improve the modeling of conformational ensembles from X-ray crystallography and cryo-EM data

   
2. Elucidating how conformational entropy influences binding specificity and catalysis.


<br>

### Modeling of Conformational Ensembles

![qFit](/static/img/pub/2023_wankowicz.jpg)

X-ray crystallography and single particle cryoEM studies collect data averaged over tens of thousands to billions of individual system copies. Each molecule within the system can adopt a different conformation (conformational heterogeneity) and may differ slightly in chemical composition (compositional heterogeneity). However, structural models generally represent the system with a single coordinate set. This simplification overlooks the multiple states present in the experimental data and consequently omits details vital to understanding protein function.

The difficulty of modeling multiple states is due to the signal-to-noise ratio in these data types. The lab develops a package, [qFit](https://github.com/ExcitedStates/qfit-3.0), which automatically detects more of the conformational ensemble and can improve the fit of the models to experimental data in high-resolution structures. We do this in collaboration with [James Fraser](https://fraserlab.com/), [Daniel Keedy](https://keedylab.org/), and [Henry van den Bedem](https://scholar.google.com/citations?user=sWo3_34AAAAJ&hl=en). Additionally, we are exploring how to leverage generative AI to improve the fitting of X-ray crystallography and cryo-EM data.

<br>


<img src="/static/img/other/Website_CCEM.png" alt="entropy" style="width: 100%; margin: 0 auto;">

### Structural Mechanisms of Conformational Entropy

Ligand specificity is foundational to the biochemistry of living organisms. However, our atomistic understanding of enzyme specificity is driven primarily by static interactions between a substrate and catalytic residues, ignoring the critical component of protein dynamics. While functional residues almost always decrease their dynamics upon binding or during catalysis (reducing entropy), the rest of the **enzyme scaffold** can increase or decrease dynamics, leading to different entropic consequences for the entire enzyme. 


<img src="/static/img/other/figure_3.png" alt="IDR_Sidechain" style="width: 100%; ; margin: 0 auto;">

The influence of dynamics is frequently underestimated because of the complexities in modeling multiple states and quantifying entropy. Our overall goal is to elucidate the role of entropy in substrate specificity and catalysis, aiming to provide a more comprehensive thermodynamic understanding of enzyme function. We attack this problem by combining our modeling strategies, machine learning, and biophysical measurements to determine how entropy influences binding specificity and catalysis.
