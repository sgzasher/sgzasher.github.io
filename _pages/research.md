---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .paper-title {
    font-weight: bold;
    font-size: 1.1em;
    display: inline;
  }
  .abstract-toggle {
    cursor: pointer;
    color: #2a7ae2;
    font-size: 0.9em;
    margin-left: 10px;
  }
  .abstract {
    display: none;
    margin-top: 10px;
    margin-bottom: 15px;
    font-size: 0.9em;
    color: #555;
    padding-left: 20px;
    border-left: 3px solid #2a7ae2;
  }
  .coauthors {
    font-style: italic;
    color: #666;
    font-size: 0.9em;
    display: inline-block;
    margin-top: 5px;
  }
</style>

## Work In Progress

### Methodology

<div class="paper-title">Automatic Partial Identification of Direct Effects under Conditional Unconfoundedness</div>
<span class="abstract-toggle" onclick="toggleAbstract(this)">Abstract</span>
<div class="abstract">
This paper develops a practical and performant algorithm for estimating sharp bounds on principal strata direct effects. I extend work on attrition problems to provide a nonparametric estimator under conditional unconfoundedness and monotonicity, more tenable assumptions than needed in popular methods for direct effect estimation. The estimator learns nuisance parameters via random forests and then learns the debiasing correction terms directly via a neural network. This approach blends the advantages of kernel-based quantile regression methods while improving finite-sample performance relative to plug-in estimation of the correction terms. I demonstrate the performance of the algorithm in simulations and apply the bounds to revisit canonical mediation problems in political science.
</div>

<div class="paper-title">Trajectory Balancing: A General Reweighting Approach to Causal Inference with Time-Series Cross-Sectional Data</div> <span class="coauthors">with Chad Hazlett and Yiqing Xu</span>

<div class="paper-title">Regression Discontinuity in Time: Theory and Minimax Estimation</div> <span class="coauthors">with Ye Wang and Yiqing Xu</span>

### Local Political Economy

<div class="paper-title">Local Institutions and the Geographic Distribution of Public Goods: Evidence from Streetview</div>

<div class="paper-title">Uncontested Elections Down the Ballot: Problems and Solutions</div>

<script>
function toggleAbstract(element) {
    var abstract = element.nextElementSibling;
    if (abstract.style.display === "none" || abstract.style.display === "") {
        abstract.style.display = "block";
        element.textContent = "Hide Abstract";
    } else {
        abstract.style.display = "none";
        element.textContent = "Show Abstract";
    }
}
</script>
<!--- 
* Minimax Adjustments for Spatial Confounding _(with Apoorva Lal)_ 
* Natural Amenities and Political Incentives: Evidence from Climate Change _(with Janet Malzahn)_
* Does Politics Need Tiebout? Local Distributive Politics and Residential Sorting
* The Chief and the Sheriff: Election vs. Appointment in Municipal Policing _(with Shun Yamaya)_
-->