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
* Ph.D in Machine Learning, TU Berlin, 2024 (expected)
* M.S. in Neural Information Processing, University T, 2019
* B.S. in Mathematics, National Tsing Hua University, 2015

Work experience
======
* 2016 - 2017: Research Assistant, Academia Sinica, Taipei, Taiwan

* 2015 - 2016: Military Service, Taiwan

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

