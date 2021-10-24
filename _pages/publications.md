---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---
I am mainly interested in how macroscopic phenomena in biological populations emerge from microscopic dynamics at the level of individuals. In particular, I investigate the following questions:

1) How do interactions at an individual level (e.g. competition, births, deaths, establishment) at different scales affect the overall population dynamics? 

2) How do we measure / describe the effect of biological mechanisms (mutation, selection, recombination, DNA degradation) on the genetic patterns and genealogies within a population?

To understand these questions, I often write down individual-based models and characterise their scaling limits as solutions to martingale problems or stochastic partial differential equations. This characterisation then provides us with further insights. To achieve this step, I employ tools and techniques from analysis and probability theory, including but not limited to random measure theory, superprocesses, convergence theorems to martingale problems, and the theory of conditionally Poisson systems with lookdown representations.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

------------
