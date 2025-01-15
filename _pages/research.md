---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
h1 {
  font-size: 1.5em;
}
h2 {
  font-size: 1.3em;
}
.paper {
  margin-bottom: 1.5em;
}
.paper-title {
  font-weight: bold;
  font-size: 0.9em;
  display: block;
}
.abstract-toggle {
  display: inline-block;
  margin-top: 0.3em;
  font-size: 0.7em;
  padding: 0 5px;
  background-color: #f0f0f0;
  border: 1px solid #ddd;
  border-radius: 3px;
  cursor: pointer;
}
.coauthors {
  display: block;
  font-size: 0.8em;
  font-style: italic;
  margin-top: 0.3em;
}
.abstract {
  display: none;
  margin-top: 0.5em;
  margin-bottom: 0.5em;
  font-size: 0.8em;
  padding-left: 1em;
}
.abstract-checkbox {
  display: none;
}
.abstract-checkbox:checked + .abstract {
  display: block;
}
</style>

# Work In Progress

## Methodology

<div class="paper">
  <span class="paper-title">Automatic Partial Identification of Direct Effects under Conditional Unconfoundedness</span>
  <label for="abstract1" class="abstract-toggle">Abstract</label>
  <input type="checkbox" id="abstract1" class="abstract-checkbox">
  <div class="abstract">
    This paper develops a practical and performant algorithm for estimating sharp bounds on principal strata direct effects. I extend work on attrition problems to provide a nonparametric estimator under conditional unconfoundedness and monotonicity, more tenable assumptions than needed in popular methods for direct effect estimation. The estimator learns nuisance parameters via random forests and then learns the debiasing correction terms directly via a neural network. This approach blends the advantages of kernel-based quantile regression methods while improving finite-sample performance relative to plug-in estimation of the correction terms. I demonstrate the performance of the algorithm in simulations and apply the bounds to revisit canonical mediation problems in political science.
  </div>
</div>

<!-- Rest of your content remains the same -->

<div class="paper">
  <span class="paper-title">Trajectory Balancing: A General Reweighting Approach to Causal Inference with Time-Series Cross-Sectional Data</span>
  <span class="coauthors">with Chad Hazlett and Yiqing Xu</span>
</div>

<div class="paper">
  <span class="paper-title">Regression Discontinuity in Time: Theory and Minimax Estimation</span>
  <span class="coauthors">with Ye Wang and Yiqing Xu</span>
</div>

## Local Political Economy

<div class="paper">
  <span class="paper-title">Local Institutions and the Geographic Distribution of Public Goods: Evidence from Streetview</span>
</div>

<div class="paper">
  <span class="paper-title">Uncontested Elections Down the Ballot: Problems and Solutions</span>
</div>



<!--- 
* Minimax Adjustments for Spatial Confounding _(with Apoorva Lal)_
* Natural Amenities and Political Incentives: Evidence from Climate Change _(with Janet Malzahn)_
* Does Politics Need Tiebout? Local Distributive Politics and Residential Sorting
* The Chief and the Sheriff: Election vs. Appointment in Municipal Policing _(with Shun Yamaya)_
-->