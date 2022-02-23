---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Minimax rate of consistency for linear models with missing values** ([paper](https://arxiv.org/pdf/2202.01463.pdf))
A. Ayme, C. Boyer, A. Dieuleveut, E. Scornet. 
*Preprint*
