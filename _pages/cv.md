---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mathematics, Your University, 2028 (expected)
* M.S. in Mathematics, Your University, 2024
* B.S. in Mathematics, Your University, 2022

Research Interests
======
* Geometric Analysis
* Partial Differential Equations
* Differential Geometry

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
