---
layout: archive
title: #"CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work / Education, retrospectively {% if site.author.linkedin %} \[ see my <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>LinkedIn</a> for details \] {% endif %}
------
* 2020 - 2025: Ph.D. in Machine Learning \
[TU Berlin](https://argmin.lis.tu-berlin.de/) / [Bosch Center for AI](https://www.bosch-ai.com/), Germany \
Advisors: [Christoph Zimmer](https://www.linkedin.com/in/christoph-zimmer-9bb236115), [Barbara Rakitsch](https://scholar.google.de/citations?user=5o957iUAAAAJ), [Marc Toussaint](https://www.user.tu-berlin.de/mtoussai/)

<!-- * 2023: Intern: Automotive Perception Active Learning \
Bosch, Stuttgart, Germany -->

<!-- * 2018: Intern: Motor Control Modeling \
Hertie Institute, Tübingen, Germany -->

* 2017 - 2019: M.S. in Neural Information Processing \
[Eberhard Karl U. of Tübingen](https://www.neuroschool-tuebingen.de/), Germany \
Advisor: [Martin Giese](https://www.compsens.uni-tuebingen.de/compsens/index.php)

* 2016 - 2017: Research Assistant \
Academia Sinica, Taipei, Taiwan

* 2015 - 2016: Military Service, Taiwan

* 2011 - 2015: B.S. in Mathematics \
National Tsing Hua U., Taiwan


Selected publications
------
{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include single-publication.html %}
  {% endif %}
{% endfor %}
