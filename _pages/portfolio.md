---
layout: archive
title: "Portfólio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Abaixo você encontra alguns dos projetos de Ciência de Dados e Estatística que desenvolvi.

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
