---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/overview.png"
---

Currently, my academic research focus on developing interpretable learning algorithm for 
soft robotic sensing and control.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
