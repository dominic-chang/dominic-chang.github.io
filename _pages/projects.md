---
layout: archive 
title: "Projects"
permalink: /projects/
author_profile: false
---

Here's a collection of personal projects that I've worked on. 

{% include base_path %}

{% for post in site.projects reversed %}
  {% include cards.html %}
{% endfor %}
