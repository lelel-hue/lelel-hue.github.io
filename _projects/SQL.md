---
layout: page
title: STA323
description: A Text-to-SQL Fine-tuning and Interactive Query System
img: assets/img/SQL.jpg
redirect: https://unsplash.com
importance: 1
category: Course Project
---

## Overview
- Final Project – Big Data Analysis Software and Application (Grade: 97)
- Processed SynSQL-2.5M, extracting 20K samples and filtering by SQL complexity, CoT density, and diversity.
- Performed Supervised Fine-Tuning (SFT) on Qwen2.5-0.5B-Instruct using Hugging Face + Ray distributed training.
- Enabled natural language → SQL generation, execution in SQLite, and bilingual explanations.

<div class="pdf-preview mt-5">
  <div class="row justify-content-center mt-4">
    <div class="col-12 col-md-10">
      <div class="ratio ratio-4x3">
        <iframe src="/assets/pdf/SQL.pdf" title="SQL Report" allowfullscreen style="width: 100%; height: 100%; border: none;"></iframe>
      </div>
    </div>
  </div>
  <div class="row justify-content-center mt-4">
    <div class="col-12 col-md-4 text-center">
      <a href="/assets/pdf/SQL.pdf" class="btn btn-primary btn-lg" download="SQL.pdf">Download the Project PDF</a>
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
