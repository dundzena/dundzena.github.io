---
layout: archive
title: "Gyvenimo aprašymas"
permalink: /lt/cv/
author_profile: true
---

{% include base_path %}

PDF: [parsisiųsti](/files/Undzenas_CV.pdf)

---

Pareigos
======
* **2026 – dabar**: Podoktorantūros mokslinis bendradarbis, Lyginamosios politikos katedra, Goethe'o universitetas Frankfurte
* **2022 – 2026**: Mokslinis bendradarbis, Kiekybinių socialinių mokslų metodų katedra, Manheimo universitetas
* **2021 – 2022**: Mokslinis asistentas, Ekonometrikos katedra, Manheimo universitetas

Išsilavinimas
======
* **2022 – 2026**: Politikos mokslų daktaras, Manheimo universitetas
  * Vadovai: Thomas Gschwend ir Richard Traunmüller
  * Disertacija: *Trumpalaikiai hierarchijos preferencijų pokyčiai ir jų politinės pasekmės*
* **2020 – 2022**: Politikos mokslų magistras, Manheimo universitetas
* **2017 – 2020**: Tarptautinių santykių su kiekybiniais tyrimo metodais bakalauras, Lidso universitetas

Publikacijos
======

**Žurnalo straipsniai ir knygų skyriai**

<ul>
{% for post in site.publications reversed %}
  {% if post.category != 'manuscripts' %}{% continue %}{% endif %}
  <li>{% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}<br>{{ post.citation }}</li>
{% endfor %}
</ul>

**Recenzuojama**

<ul>
{% for post in site.publications reversed %}
  {% if post.category != 'under_review' %}{% continue %}{% endif %}
  <li>{% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}<br>{{ post.citation }}</li>
{% endfor %}
</ul>

**Darbo straipsniai**

<ul>
{% for post in site.publications reversed %}
  {% if post.category != 'working_papers' %}{% continue %}{% endif %}
  <li><em>{{ post.title }}</em><br>{{ post.citation }}</li>
{% endfor %}
</ul>

Dėstymas
======

<ul>
{% for post in site.teaching reversed %}
  <li><strong>{{ post.title }}</strong> ({{ post.type }}), {{ post.venue }}.<br>{{ post.content | strip_html | strip }}</li>
{% endfor %}
</ul>

Kompetencijos
======
* **Programavimas**: R, Python, SQL
* **Statistika**: MKI, didžiausio tikėtinumo metodas, Bajeso statistika, neparametrinė statistika, daugialypiai modeliai, atsitiktiniai miškai, neuroniniai tinklai, struktūrinė temų modeliacija, Monte Karlo simuliacijos, struktūrinės lygčių modeliai, tinklo analizė
* **Tyrimo dizainas**: Apklausų eksperimentai, laboratoriniai eksperimentai, regresinė diskontinuacija, instrumentiniai kintamieji, netikėti įvykiai apklausos metu, skirtumų-skirtumų metodas, derinimas
* **Duomenų vizualizacija**: ggplot2, R, Matplotlib, Seaborn, Stata
* **Programinė įranga**: RStudio, VS Code, Jupyter Notebooks, Stata, LaTeX, Git
* **Kalbos**: Lietuvių (C2), anglų (C2), vokiečių (A2)
