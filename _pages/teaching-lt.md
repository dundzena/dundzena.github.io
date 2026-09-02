---
layout: archive
title: "Dėstymas"
permalink: /lt/teaching/
author_profile: true
---

{% include base_path %}

<ul>
{% for post in site.teaching reversed %}
  <li><strong>{{ post.title }}</strong> ({{ post.type }}), {{ post.venue }}.<br>{{ post.content | strip_html | strip }}</li>
{% endfor %}
</ul>
