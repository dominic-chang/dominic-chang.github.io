---
layout: archive 
title: "Projects"
permalink: /projects/
author_profile: false
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include cards.html %}
{% endfor %}
