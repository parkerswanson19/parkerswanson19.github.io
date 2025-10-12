---
layout: page
title: work
permalink: /work/
description: Some things I've worked on.
nav: true
nav_order: 3
horizontal: false
---

<style>
  .work-gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  .work-item {
    width: 220px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    background: #f8f8f8;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
  }

  .work-item:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  }

  .work-item img {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain;
  }

  @media (max-width: 600px) {
    .work-item {
      width: 150px;
      height: 90px;
    }
  }
</style>

<div class="work-gallery">
  <a href="https://www.moment.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/Moment.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.datadoghq.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/datadog-cover.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.seafare.io" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/Seafare.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.salesforce.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/Salesforce-logo.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.curatesolutions.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/curate.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.capitalone.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/capital-one.jpg" class="img-fluid" %}
  </a>

  <a href="https://www.liquidspace.com" target="_blank" class="work-item" rel="noopener">
    {% include figure.html path="assets/work/liquidspace.jpg" class="img-fluid" %}
  </a>
</div>
