---
layout: archive
title: "Portfólio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% assign portfolio_items = site.portfolio | sort: "date" | reverse %}

<div class="grid__wrapper">
  {% for post in portfolio_items %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
