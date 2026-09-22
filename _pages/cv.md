---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

`2024 — present`  PhD in Signal Processing and Telecommunications  
CY Cergy Paris University, Cergy, France  
**Thesis:** "*Low energy precoding for centralized and distributed multi-user massive MIMO systems*"

`2023 — 2024`  MSc in Signal Processing, Information Theory, and Telecommunications  
CY Cergy Paris University, Cergy, France

`2021 — 2024`
Engineering degree in Signal Processing and Artificial Intelligence  
ENSEA, Cergy, France

## Research interests

- Massive MIMO and wireless communications
- Signal processing for communications
- Power amplifiers and nonlinear distortion
- Energy-efficient 5G/6G networks

Publications
======

  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
<!-- Talks
======
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %} -->
  
Teaching
======

  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Skills
======

**Programming:** Python, MATLAB

**Scientific tools:** LaTeX, Git, ...

**Languages:** French, English, Italian, Spanish
