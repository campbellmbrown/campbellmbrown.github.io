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
