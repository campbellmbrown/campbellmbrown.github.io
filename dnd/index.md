---
layout: page
title: D&D One-Shots
permalink: /dnd/
---

Welcome to my D&D gallery!

{% for oneshot in site.dnd %}
- [{{ oneshot.title }}]({{ oneshot.url }})  
  {{ oneshot.description }}
{% endfor %}

<iframe src="https://drive.google.com/file/d/1nhK2KecFs9gQuwmfdxtyt4nVqyezXBp-/preview" width="640" height="480" allow="autoplay"></iframe>

