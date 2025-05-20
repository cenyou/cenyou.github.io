---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work / Education {% if site.author.linkedin %} \[ see my <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>LinkedIn</a> for details \] {% endif %}
------
* 2020 - 2025 &emsp; Ph.D. in Machine Learning, [TU Berlin](https://argmin.lis.tu-berlin.de/) & [Bosch Center for AI](https://www.bosch-ai.com/), Germany \
  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;
  Advisors: [Christoph Zimmer](https://www.linkedin.com/in/christoph-zimmer-9bb236115), [Barbara Rakitsch](https://scholar.google.de/citations?user=5o957iUAAAAJ), [Marc Toussaint](https://www.user.tu-berlin.de/mtoussai/)

* 2017 - 2019 &emsp; M.Sc. in Neural Information Processing, [Eberhard Karl University of Tübingen](https://www.neuroschool-tuebingen.de/), Germany \
  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;
  Advisor: [Martin Giese](https://www.compsens.uni-tuebingen.de/compsens/index.php)

* 2016 - 2017 &emsp; Research Assistant, Academia Sinica, Taipei, Taiwan

* 2015 - 2016 &emsp; Military Service, Taiwan

* 2011 - 2015 &emsp; B.Sc. in Mathematics, National Tsing Hua University, Taiwan


Selected publications
------
{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include single-publication.html %}
  {% endif %}
{% endfor %}
