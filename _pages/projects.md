---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign sorted = (site.projects | sort: 'orderdate') | reverse %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
