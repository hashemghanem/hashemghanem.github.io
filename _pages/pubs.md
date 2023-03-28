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

{% for post in site.conferences reversed %}
  {% include archive-single.html %}
{% endfor %}


