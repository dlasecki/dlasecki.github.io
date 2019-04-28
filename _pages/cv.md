---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in Computing, Poznan University of Technology, 2013-2017
* B.Sc. in Physics, Adam Mickiewicz University, 2015-2017
* MMath in Combinatorics & Optimization (Quantum Information), University of Waterloo, 2017-2019 (expected)

Work experience
======
* 2017-...: Research Assistant
  * University of Waterloo (Institute for Quantum Computing)
  * Duties included: research
  * Supervisor: Professor Debbie Leung

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
