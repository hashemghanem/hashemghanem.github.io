---
permalink: /pubs/
title: "Publications"
excerpt: "This is a page not in th emain menu"
author_profile: true
redirect_from: 
  - "/nmp/"
  - "/nmp.html"
---



Conferences: 
======
Hashem Ghanem, Nicolas Keriven, Nicolas Tremblay. **Fast Graph Kernel with Optical Random Features** . In ICASSP, 2021. ([pdf](https://arxiv.org/pdf/2010.08270.pdf))

{% include base_path %}

## Preprint

{% for post in site.preprint reversed %}
  {% include archive-single.html %}
{% endfor %}
