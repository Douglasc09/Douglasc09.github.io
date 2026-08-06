---
layout: archive
title: "Portfólio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% assign portfolio_sorted = site.portfolio | sort: "date" | reverse %}

<div class="grid__wrapper">
  {% for post in portfolio_sorted %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
