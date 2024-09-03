---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: false
---

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

{% if site.talkmap_link == true %}

<iframe src="/talkmap/map.html" style="display:block;width:calc(100% - 50px);max-width:850px;;height:30em;border:none;margin:auto"></iframe>


{% endif %}

