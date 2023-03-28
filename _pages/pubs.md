---
layout: archive
title: ""
permalink: /pubs/
author_profile: true
---

# Preprint: 

{% include base_path %}

{% for post in site.preprint reversed %}
  {% include archive-single.html %}
{% endfor %}


# Conferences: 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Hashem Ghanem, Nicolas Keriven, Nicolas Tremblay. **Fast Graph Kernel with Optical Random Features** . In ICASSP, 2021. ([pdf](https://arxiv.org/pdf/2010.08270.pdf))

