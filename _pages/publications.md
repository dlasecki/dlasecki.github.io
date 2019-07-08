---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}

{% for post in site.publicationss reversed %}
  {% include archive-single.html %}
{% endfor %}

