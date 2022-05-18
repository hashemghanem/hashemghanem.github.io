---
layout: archive
title: "Publications here"
permalink: /pubs/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Pre-print

{% include base_path %}

{% for post in site.preprint reversed %}
  {% include archive-single.html %}
{% endfor %}
