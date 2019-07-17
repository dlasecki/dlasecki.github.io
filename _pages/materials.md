---
layout: archive
title: "Materials"
permalink: /materials/
author_profile: true
---
Below you can find some write-ups or projects I created. Mostly, they were prepared for courses that I completed. Their goal was to summarize an existing paper or to prove a selected theorem in a detailed, accessible way. Maybe someone will find them useful.

{% include base_path %}

{% for post in site.materials reversed %}
  {% include archive-single.html %}
{% endfor %}

