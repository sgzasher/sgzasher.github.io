---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .page__content h2 {
    border-bottom: 1px solid #f2f3f3;
    padding-bottom: 0.5em;
    margin-top: 2em;
  }
  .page__content h3 {
    margin-top: 1.5em;
  }
  .page__content h4 {
    margin-top: 1em;
    margin-bottom: 0.5em;
    font-size: 1.5em;  /* Adjust this value as needed */
  }
  details {
    margin-top: 0.5em;
    margin-bottom: 1em;
  }
  summary {
    cursor: pointer;
    font-weight: italic;
    font-size: 0.9em;  /* Make the abstract button smaller */
  }
  details p {
    margin-top: 0.5em;
    margin-left: 1em;
    font-style: italic;
    font-size: 0.9em;  /* Make the abstract text slightly smaller */
  }
  .coauthors {
    font-size: 0.9em;
    color: #666;
    font-style: italic;
  }
</style>

## Work In Progress

### Methodology

#### Automatic Partial Identification of Direct Effects under Conditional Unconfoundedness

<details>
  <summary>Abstract</summary>
  <p>This paper develops a practical and performant algorithm for estimating sharp bounds on principal strata direct effects. I extend work on attrition problems to provide a nonparametric estimator under conditional unconfoundedness and monotonicity, more tenable assumptions than needed in popular methods for direct effect estimation. The estimator learns nuisance parameters via random forests and then learns the debiasing correction terms directly via a neural network. This approach blends the advantages of kernel-based quantile regression methods while improving finite-sample performance relative to plug-in estimation of the correction terms. I demonstrate the performance of the algorithm in simulations and apply the bounds to revisit canonical mediation problems in political science.</p>
</details>

#### Trajectory Balancing: A General Reweighting Approach to Causal Inference with Time-Series Cross-Sectional Data
<span class="coauthors">with Chad Hazlett and Yiqing Xu</span>

#### Regression Discontinuity in Time: Theory and Minimax Estimation
<span class="coauthors">with Ye Wang and Yiqing Xu</span>

### Local Political Economy

#### Local Institutions and the Geographic Distribution of Public Goods: Evidence from Streetview

#### Uncontested Elections Down the Ballot: Problems and Solutions

<!--- 
* Minimax Adjustments for Spatial Confounding _(with Apoorva Lal)_ 
* Natural Amenities and Political Incentives: Evidence from Climate Change _(with Janet Malzahn)_
* Does Politics Need Tiebout? Local Distributive Politics and Residential Sorting
* The Chief and the Sheriff: Election vs. Appointment in Municipal Policing _(with Shun Yamaya)_
-->