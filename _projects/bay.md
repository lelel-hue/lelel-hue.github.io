---
layout: page
title: STA306
description: Article Reproduction: A Bayesian State-Space Formulation of Dynamic Occupancy Models
img: assets/img/bay.png
importance: 7
category: Crouse Project
---

## Overview
- Final Project – Bayesian Statistics (Grade: 93)
- We reproduced the Bayesian state-space framework to estimate dynamic occupancy, extinction, and colonization rates while addressing detection errors.
- Using the European Crossbill dataset, MCMC with Gibbs sampling analyzes temporal and spatial occupancy dynamics.
- Environmental covariates (e.g., precipitation, temperature) are integrated to improve model performance, assessed via DIC.

<div class="pdf-preview mt-5">
  <div class="row justify-content-center mt-4">
    <div class="col-12 col-md-10">
      <div class="ratio ratio-4x3">
        <iframe src="/assets/pdf/bay.pdf" title="bay Report" allowfullscreen style="width: 100%; height: 100%; border: none;"></iframe>
      </div>
    </div>
  </div>
  <div class="row justify-content-center mt-4">
    <div class="col-12 col-md-4 text-center">
      <a href="/assets/pdf/bay.pdf" class="btn btn-primary btn-lg" download="bay.pdf">Download Project PDF</a>
    </div>
  </div>
</div>

<style>
  .pdf-preview .ratio {
    max-width: 100%;
    height: 800px;
  }

  .btn {
    display: inline-block;
    margin: 0 auto;
  }

  @media (max-width: 768px) {
    .pdf-preview .ratio {
      height: calc(100vh - 150px); /* Adjust height for smaller screens */
    }
  }
</style>
