---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.paper {
  margin-bottom: 20px;
}
.title-row {
  display: flex;
  align-items: baseline;
  flex-wrap: wrap;
}
.abstract-toggle {
  margin-left: 10px;
  cursor: pointer;
  background-color: #f0f0f0;
  padding: 2px 5px;
  border-radius: 3px;
  font-size: 0.7em;
  border: 1px solid #ddd;
}
.abstract-checkbox {
  display: none;
}
.abstract {
  display: none;
  margin-top: 10px;
  width: 100%;
}
.abstract-checkbox:checked + .abstract {
  display: block;
}
.coauthors {
  font-size: 0.9em;
  font-weight: normal;
  margin-left: 10px;
}
h3 {
  margin: 0;
  display: inline;
}
</style>



# Work In Progress

## Methodology

<div class="paper">
  <div class="title-row">
    <h3>Automatic Partial Identification of Direct Effects under Conditional Unconfoundedness</h3>
    <label for="abstract1" class="abstract-toggle">Abstract</label>
  </div>
  <input type="checkbox" id="abstract1" class="abstract-checkbox">
  <div class="abstract">
    This paper develops a practical and performant algorithm for estimating sharp bounds on principal strata direct effects. I extend work on attrition problems to provide a nonparametric estimator under conditional unconfoundedness and monotonicity, more tenable assumptions than needed in popular methods for direct effect estimation. The estimator learns nuisance parameters via random forests and then learns the debiasing correction terms directly via a neural network. This approach blends the advantages of kernel-based quantile regression methods while improving finite-sample performance relative to plug-in estimation of the correction terms. I demonstrate the performance of the algorithm in simulations and apply the bounds to revisit canonical mediation problems in political science.
  </div>
</div>

<div class="paper">
  <div class="title-row">
    <h3>Trajectory Balancing: A General Reweighting Approach to Causal Inference with Time-Series Cross-Sectional Data</h3>
    <span class="coauthors">with Chad Hazlett and Yiqing Xu</span>
  </div>
</div>

<div class="paper">
  <div class="title-row">
    <h3>Regression Discontinuity in Time: Theory and Minimax Estimation</h3>
    <span class="coauthors">with Ye Wang and Yiqing Xu</span>
  </div>
</div>

## Local Political Economy

<div class="paper">
  <div class="title-row">
    <h3>Local Institutions and the Geographic Distribution of Public Goods: Evidence from Streetview</h3>
  </div>
</div>

<div class="paper">
  <div class="title-row">
    <h3>Uncontested Elections Down the Ballot: Problems and Solutions</h3>
  </div>
</div>



<!--- 
* Minimax Adjustments for Spatial Confounding _(with Apoorva Lal)_
* Natural Amenities and Political Incentives: Evidence from Climate Change _(with Janet Malzahn)_
* Does Politics Need Tiebout? Local Distributive Politics and Residential Sorting
* The Chief and the Sheriff: Election vs. Appointment in Municipal Policing _(with Shun Yamaya)_
-->