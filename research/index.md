---
title: Research in the Wankowicz Lab
layout: default
group: research
---


<br>
<br>

## The lab is interested in determining the mechanisms driving the binding specificity and catalysis, viewing this problem from a thermodynamic and structural lens. 




   

<br>

### Developing novel algorithms to detect conformational ensembles in experimental data

<img src="/static/img/other/ML_Ensemble.jpg" alt="Algorithm Development" style="width: 100%; margin: 0 auto;">
<br>
<br>

X-ray crystallography and single particle cryoEM studies collect data averaged over tens of thousands to billions of individual system copies. Each molecule within the system can adopt a different conformation (conformational heterogeneity) and may differ slightly in chemical composition (compositional heterogeneity). However, structural models generally represent the system with a single coordinate set. This simplification overlooks the multiple states present in the experimental data and consequently omits details vital to understanding protein function. The difficulty of modeling multiple states is due to the signal-to-noise ratio in these data types. 

The lab develops a software package, [qFit](https://github.com/ExcitedStates/qfit-3.0), which automatically detects more of the conformational ensemble and can improve the fit of the models to experimental data in high-resolution structures. We do this in collaboration with [James Fraser](https://fraserlab.com/), [Daniel Keedy](https://keedylab.org/), and [Henry van den Bedem](https://scholar.google.com/citations?user=sWo3_34AAAAJ&hl=en). 

![qFit](/static/img/pub/2023_wankowicz.jpg)

<br>





### Connecting structures to thermodynamic biophysical binding measurements

Most conclusions about protein function, binding affinity predictions, and mutations' impact are based only on enthalpic parameters, encompassing only 50% of free energy. For example, suppose the binding of two highly related ligands differs by a hydrogen bond. In that case, it is often predicted that the ligand with an additional hydrogen bond has a higher binding affinity. However, this bond only tells part of the story of why binding affinity changes. One key reason enthalpic changes are favored is that quantitative metrics can be extracted from structural models, allowing easy use of these metrics' computational algorithms, such as binding prediction or ligand docking. However, equivalent metrics currently do not exist for entropy, preventing us from explicitly incorporating entropy into our structural intuition of binding. Our goal is to change this paradigm.

<img src="/static/img/other/entropy_biophysical.jpg" alt="Entropy Biophysical Measurements" style="width: 100%; margin: 0 auto;">

<br>
<br>






### How does the entire conformational ensemble impact binding specificity and catalysis?

Ligand specificity is foundational to the biochemistry of living organisms. However, our atomistic understanding of enzyme specificity is driven primarily by static interactions between a substrate and catalytic residues, ignoring the critical component of protein dynamics. While functional residues almost always decrease their dynamics upon binding or during catalysis (reducing entropy), the rest of the **enzyme scaffold** can increase or decrease dynamics, leading to different entropic consequences for the entire enzyme. 
<img src="/static/img/other/figure_3.png" alt="IDR_Sidechain" style="width: 100%; ; margin: 0 auto;">

<br>

Leveraging machine learning, bioinformatics, and experimental approaches, we aim to identify how conformational ensembles, considering the enthalpic and entropic portion, impact binding specificity and catalysis. Our overall goal is to elucidate the role of entropy in substrate specificity and catalysis, aiming to provide a more comprehensive thermodynamic understanding of enzyme function. 

<img src="/static/img/other/ML_Kinases.jpg" alt="ML_Kinases" style="width: 100%; ; margin: 0 auto;">

