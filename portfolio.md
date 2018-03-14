---
layout: splash
title: Portfolio
permalink: /portfolio/index.html
classes:
  - landing
  - air

---



{% for item in site.portfolio %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">view project</a></p>
{% endfor %}