---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PDF: [download](/files/Undzenas_CV.pdf)

---

Positions
======
* **2026 – present**: Postdoctoral Research Associate, Chair of Comparative Politics, Goethe University Frankfurt
* **2022 – 2026**: Research Associate, Chair of Quantitative Methods in the Social Sciences, University of Mannheim
* **2021 – 2022**: Research Assistant, Chair of Econometrics, University of Mannheim

Education
======
* **2022 – 2026**: Doctorate in Political Science, University of Mannheim
* **2020 – 2022**: M.A. in Political Science, University of Mannheim
* **2017 – 2020**: B.A. in International Relations with Quantitative Research Methods, University of Leeds

Publications
======

**Journal Articles & Book Chapters**

  <ul>{% for post in site.publications reversed %}
    {% if post.category != 'manuscripts' %}{% continue %}{% endif %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

**Under Review**

  <ul>{% for post in site.publications reversed %}
    {% if post.category != 'under_review' %}{% continue %}{% endif %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

**Working Papers**

  <ul>{% for post in site.publications reversed %}
    {% if post.category != 'working_papers' %}{% continue %}{% endif %}
    <li><em>{{ post.title }}</em>{% if post.citation %} — {{ post.citation }}{% endif %}</li>
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Programming**: R, Python, SQL
* **Statistics**: OLS, maximum likelihood, Bayesian statistics, non-parametric statistics, multi-level models, random forests, neural networks, structural topic modelling, Monte Carlo simulations, SEM, formal modelling, network analysis
* **Research design**: Survey experiments, lab experiments, regression discontinuity, instrumental variables, unexpected events during surveys, difference-in-differences, matching
* **Data visualisation**: ggplot2, Base R, Matplotlib, Seaborn, Stata
* **Software**: RStudio, VS Code, Jupyter Notebooks, Stata, LaTeX, Git
* **Natural languages**: Lithuanian (C2), English (C2), German (A2)


