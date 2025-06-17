---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher at the [Finnish Center for AI (FCAI)](https://fcai.fi), working with [Luigi Acerbi](https://lacerbi.github.io/) ([Machine and Human Intelligence Group](https://www.helsinki.fi/en/researchgroups/machine-and-human-intelligence)) and [Samuel Kaski](https://kaski-lab.com/) ([Probabilistic Machine Learning Group](https://research.cs.aalto.fi/pml/)), along with other collaborators.
My research focuses on probabilistic machine learning, with particular interests in amortized Bayesian inference, learning from synthetic data, and adaptive experimental design.

I did my PhD at the [Bosch Center for AI](https://www.bosch-ai.com/) & [TU Berlin](https://argmin.lis.tu-berlin.de/), working with [Christoph Zimmer](https://www.linkedin.com/in/christoph-zimmer-9bb236115), [Barbara Rakitsch](https://scholar.google.de/citations?user=5o957iUAAAAJ), and [Marc Toussaint](https://www.user.tu-berlin.de/mtoussai/).
My PhD research focused on Bayesian active learning, particularly under constraints, using Gaussian processes, neural networks, and synthetic data.

Before this, I pursued a Master’s in [Computational Neuroscience at the University of Tübingen](https://www.neuroschool-tuebingen.de/), supported by the prestigious [Tsung Cho Chang Foundation scholarship](https://www.daad.org.tw/zh/tcc-stipendium/), awarded to only five students in Taiwan each year.
My Master's thesis, supervised by [Martin Giese](https://www.compsens.uni-tuebingen.de/compsens/index.php), developed an explainable neural network model for encoding biological motor control.
I completed my undergraduate studies in mathematics at National Tsing Hua University and also spent a year developing database web interfaces while assisting in neurogenetics research.

Research interests
------
* Bayesian Inference, Bayesian Inference with Deep Learning
* Active Learning, Bayesian Optimization, Adaptive Experimental Design
* Amortized / Pretrained Bayesian Approaches

Selected publications
------
{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include single-publication.html %}
  {% endif %}
{% endfor %}

