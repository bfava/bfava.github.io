---
permalink: /
title: "Bruno Fava"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
layout: archive
---

I'm a PhD Candidate in the Economics Department at Northwestern University. My main interest is in Econometrics with applications to Development Economics.

Working Papers
======
<ol>
  <li>Predicting the Distribution of Treatment Effects: A Covariate-Adjustment Approach <a href="https://arxiv.org/abs/2407.14635" target="_blank">[arxiv]</a> <a href="https://drive.google.com/file/d/18xZ5d0_dP2jdgYQwgVS7Kq-J1Uv0t0rV/view?usp=share_link" target="_blank">[Presentation MEG 2024]</a> <button onclick="toggleAbstract('abstract_dte', 'arrowNew')" style="font-family: sans-serif; background-color: transparent; border: none; color: black; cursor: pointer; display: inline;">Abstract <span id="arrowNew" style="color: #ADD8E6;">▶</span></button><br>

  <p>
    <strong>Best Student Paper Award</strong> at the <em>32nd Midwest Econometrics Group Annual Conference (2024)</em>
  </p>

  <div id="abstract_dte" style="display:none; margin-top: 5px; margin-left: 20px;">
  <p>Important questions for impact evaluation require knowledge not only of average effects, but of the distribution of treatment effects. What proportion of people are harmed? Does a policy help many by a little? Or a few by a lot? The inability to observe individual counterfactuals makes these empirical questions challenging. But what if counterfactuals can be predicted? I propose an approach to inference on points of the distribution of treatment effects that incorporates predicted individual impacts through covariate adjustment. I show the approach is flexible in that any machine learning algorithm can be used: if predictions are accurate, the resulting confidence interval is small; if predictions are poor, it is wide but valid. Finally, I revisit five RCTs in microcredit and find evidence that, on average, at least 12.5% of the study populations were negatively affected by the treatment (3.5% if covariates are not considered) and at least 13.6% benefited (5.3%).</p>
  </div>
  </li>
</ol>

Publications
======
<ol>
  <li>Probabilistic Nearest Neighbors Classification <a href="https://doi.org/10.3390/e26010039" target="_blank">[pdf]</a> <a href="https://github.com/paulocmarquesf/pnnclass" target="_blank">[R Package]</a> <button onclick="toggleAbstract('abstract1', 'arrow1')" style="font-family: sans-serif; background-color: transparent; border: none; color: black; cursor: pointer; display: inline;">Abstract <span id="arrow1" style="color: #ADD8E6;">▶</span></button><br>
  (With Paulo C. Marques F. and Hedibert F. Lopes)
  Entropy, 2024, 26, 39.

  <div id="abstract1" style="display:none; margin-top: 5px; margin-left: 20px;">
  <p>Analysis of the currently established Bayesian nearest neighbors classification model points to a connection between the computation of its normalizing constant and issues of NP-completeness. An alternative predictive model constructed by aggregating the predictive distributions of simpler nonlocal models is proposed, and analytic expressions for the normalizing constants of these nonlocal models are derived, ensuring polynomial time computation without approximations. Experiments with synthetic and real datasets showcase the predictive performance of the proposed predictive model.</p>
  </div>
  </li>

  <li>The Illusion of the Illusion of Sparsity: An exercise in prior sensitivity <a href="https://projecteuclid.org/journals/brazilian-journal-of-probability-and-statistics/volume-35/issue-4/The-illusion-of-the-illusion-of-sparsity--An-exercise/10.1214/21-BJPS503.full" target="_blank">[pdf]</a> <a href="https://github.com/bfava/IllusionOfIllusion" target="_blank">[code]</a><button onclick="toggleAbstract('abstract2', 'arrow2')" style="font-family: sans-serif; background-color: transparent; border: none; color: black; cursor: pointer; display: inline;">Abstract <span id="arrow2" style="color: #ADD8E6;">▶</span></button><br>
  (With Hedibert F. Lopes)
  Brazilian Journal of Probability and Statistics, 2021, Vol. 35, No. 4, 699-720.

  <div id="abstract2" style="display:none; margin-top: 5px; margin-left: 20px;">
  <p>The emergence of Big Data raises the question of how to model economic relations when there is a large number of possible explanatory variables. We revisit the issue by comparing the possibility of using dense or sparse models in a Bayesian approach, allowing for variable selection and shrinkage. More specifically, we discuss the results reached by Giannone, Lenza and Primiceri (2020) through a “Spike-and-Slab” prior, which suggest an “illusion of sparsity” in Economics datasets, as no clear patterns of sparsity could be detected. We make a further revision of the posterior distributions of the model, and propose three experiments to evaluate the robustness of the adopted prior distribution. We find that the pattern of sparsity is sensitive to the prior distribution of the regression coefficients, and present evidence that the model indirectly induces variable selection and shrinkage, which suggests that the “illusion of sparsity” could be, itself, an illusion. Code is available on Github.</p>
  </div>
  </li>
</ol>

<script>
function toggleAbstract(abstractId, arrowId) {
  var abstract = document.getElementById(abstractId);
  var arrow = document.getElementById(arrowId);
  if (abstract.style.display === "none") {
    abstract.style.display = "block";
    arrow.innerHTML = "▼";
  } else {
    abstract.style.display = "none";
    arrow.innerHTML = "▶";
  }
}
</script>


Work in Progress
======
<ol>
  <li>Algorithmic Bias in Microcredit: Consequences of Data-Driven Lending Practices <br>
  (With Susan Athey, Dean Karlan, Adam Osman and Jonathan Zinman)
  </li>
</ol>
