---
title: Research in the Wankowicz Lab
layout: default
group: research
---

<div class="container my-4">
  
  <div class="row">
    <div class="col">
      <h2>Research in the Wankowicz Lab</h2>
      <p>The lab has two main areas of research:</p>
      <ul>
        <li>Developing software to improve the modeling of conformational ensembles from X-ray crystallography and cryo-EM data</li>
        <li>Elucidating how conformational entropy influences binding specificity and catalysis</li>
      </ul>
    </div>
  </div>

  <div class="row my-4">
    <div class="col-md-12">
      <h3>Modeling of Conformational Ensembles</h3>
      <img class="img-fluid mx-auto d-block" src="/static/img/pub/2023_wankowicz.jpg" alt="qFit" style="display: block; margin: 0 auto;">
      <p class="mt-3">
        X-ray crystallography and single particle cryoEM studies collect data averaged over tens of thousands to billions of individual system copies. Each molecule within the system can adopt a different conformation (conformational heterogeneity) and may differ slightly in chemical composition (compositional heterogeneity). However, structural models generally represent the system with a single coordinate set. This simplification overlooks the multiple states present in the experimental data and consequently omits details vital to understanding protein function.
      </p>
      <p>
        The difficulty of modeling multiple states is due to the signal-to-noise ratio in these data types. The lab develops a package, <a href="https://github.com/ExcitedStates/qfit-3.0">qFit</a>, which automatically detects more of the conformational ensemble and can improve the fit of the models to experimental data in high-resolution structures. We do this in collaboration with <a href="https://fraserlab.com/">Fraser</a> and <a href="https://keedylab.org/">Keedy</a> labs. Additionally, we are exploring how to leverage generative AI to improve the fitting of X-ray crystallography and cryo-EM data.
      </p>
    </div>
  </div>

  <div class="row my-4">
    <div class="col-md-12">
      <h3>Structural Mechanisms of Conformational Entropy</h3>
      <p>
        The understanding of ligand specificity is foundational to the biochemistry of living organisms. However, our atomistic understanding of enzyme specificity is driven primarily by static interactions between a substrate and catalytic residues, ignoring the critical component of protein dynamics. Dynamics affect binding and catalysis by enabling proteins to access various states and altering the thermodynamics associated with these processes through entropy. However, the influence of dynamics is frequently underestimated because of the complexities in modeling multiple states and quantifying entropy. Our overall goal is to leverage the conformational modeling improvements we make to elucidate the role of entropy in substrate recognition and catalysis, aiming to provide a more comprehensive thermodynamic understanding of enzyme function.
      </p>
      <p>
        We attack this problem by combining our modeling strategies, machine learning, and biophysical measurements to determine how entropy influences binding specificity and catalysis.
      </p>
    </div>
  </div>

</div>
