---
layout: page
title: Portfolio
permalink: /portfolio/
---

{% for portfolio in site.portfolio %}
  <h1><a href="{{ portfolio.url }}">{{ portfolio.title}}</a>
  <a href="portfolio.github">{% include icon-github.html %}</a></h1>
  

  {{ portfolio.description }}
{% endfor %}
