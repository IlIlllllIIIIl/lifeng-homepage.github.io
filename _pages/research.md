---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Black Hole Thermodynamics and Statistical Physics
------
Advisor: *Prof. Jun Nian @[International Centre for Theoretical Physics Asia-Pacific](https://ictp-ap.org/)*

**Project Outline**

This program focuses on the study of black hole thermodynamics, derivation of the black hole microphysics and logarithm corrections. We establish black hole statistical mechanics via conformal field theory at certain black hole boundaries and thus give boundary quantum description of the black hole entropy.

*Sponsored by [Chinese Academy of Sciences](https://english.cas.cn/)*


Perturbative Methods in Gravitational Lensing
------
Advisor: *Prof. Junji Jia @[Center for Theoretical Physics, Wuhan University](http://202.114.78.174/ctp/)*

**Project Outline**

This research concentrates on developing perturbative methods in weak gravitational lensing to calculate the measurable quantities such as deflection angle and time delay. We calculate the applications in general theories of gravity where quantum corrections are considered.

*Sponsored by the Government of Hubei Province*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
